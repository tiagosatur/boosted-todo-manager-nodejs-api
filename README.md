# Boosted Todo Manager Nodejs API

## About this challenge

In this challenge you will work more deeply with middlewares in Express. That way you will be able to further secure the knowledge gained so far.

To make the business rule a little easier, you'll work with the same application from the previous challenge: an application to manage tasks (or all ) but with some changes.

It will be allowed to create a user with name and username , as well as to CRUD all:

- Create a new todo;
- List all all;
- Change the title and deadline of an existing todo;
- Mark a todo as done;
- Delete a todo;

All of this for each specific user. In addition, this time we will have a free plan where the user can only create up to ten all and a Pro plan that will allow you to create unlimited all , all this using middleware to make the necessary validations.

We'll look in more detail below at what needs to be done and how

## Application template

To help you with this challenge, we've created this template for you that you should use as a GitHub template.

The template is available at the following URL: [https://github.com/rocketseat-education/ignite-template-trabalhando-com-middlewares](https://github.com/rocketseat-education/ignite-template-trabalhando-com-middlewares)

Tip: If you don't know how to use GitHub repositories as a template, we have a guide in our FAQ. Now navigate to the created folder, open it in Visual Studio Code and finally open the index.js file . Remember to run the yarn command on your terminal to install all dependencies and you will have the following code:
![https://i.imgur.com/xRNTZRw.png](src/index.js code image)

## Application Middlewares

With the template already cloned and the index.js file open, you must complete where there is no code with the code to achieve the objectives of each test.

In this challenge it will not be necessary to change the code of any route, only the middlewares. The tests will also test the operation of the routes but the result depends `only on the middlewares`.

### checksExistsUserAccount

This middleware is responsible for receiving the username of the user by the header and validating whether or not there is a user with the username passed. If it exists, the user must be transferred to the request and the next function must be called.

### checksCreateTodosUserAvailability

This middleware must receive the user already inside the request and call the function next only if this user is still in the free plan and does not have 10 all registered or if he already has the Pro plan activated .

### checksTodoExists

This middleware must receive the username from within the header and the id of a whole from within `request.params`. You must validate the user, validate that the `id` is a uuid and also validate that this id belongs to a whole of the informed user.

With all validations passing, the whole found must be passed to the `request` as well as the user found as well and the next function must be called.

### findUserById

This middleware has a similar operation to the `checksExistsUserAccount` middleware, but the search for the user must be done through a user id passed by a parameter in the route. If the user has been found, it must be passed into `request.user` and the next function must be called.

## Test Specification

In each test, you have a brief description of what your application must do for the test to pass.

For this challenge, we have the following tests:

### Middleware tests

- Should be able to find user by username in header and pass it to request.user
  - For this test to pass, you must allow the checksExistsUserAccount middleware to receive a username through the request header and if a user with the same username exists, it must be placed inside request.user and, at the end, return the next function call. .
  - Pay attention to the name of the property that will store the user object in the request.
- Should not be able to find a non existing user by username in header
  - For this test to pass, in the checksExistsUserAccount middleware you must return a response with status 404 if the username passed in the request header does not belong to any user. You can also return an error message, but this is optional.
- Should be able to let user create a new todo when is in free plan and have less than ten todos
  - For this test to pass, you must allow the checksCreateTodosUserAvailability middleware to receive the user object (consider whenever the object exists) from the request and call the next function only in case the user is in the free plan and does not have 10 all registered or if he already has the Pro plan activated .
  - You can check whether the user has a Pro plan or not from the `user.pro` property . If it is true it means that the Pro plan is in use.
- Should not be able to let user create a new todo when is not Pro and already have ten todos
  - For this test to pass, in the checksCreateTodosUserAvailability middleware you must return a response with status 403 if the user received by the request is in the free plan and has already 10 all registered . You can also return an error message, but this is optional.
- Should be able to let user create infinite new todos when is in Pro plan
  - For this test to pass, you must allow the checksCreateTodosUserAvailability middleware to receive the user object (consider whenever the object exists) from the request and call the next function if the user already has the Pro plan.
  - If you passed the two previous tests before this one, it should already pass too.
- Should be able to put user and todo in request when both exits
  - For this test to pass, the checksTodoExists middleware must receive the username from within the header and the id of a whole from within request.params . You must validate that the user exists, validate that the id is a uuid and also validate that this id belongs to a whole of the informed user.
  - With all validations passing, the whole found must be passed to the request as well as the user found as well and the next function must be called.
  - It is important that you put in request.user the user found and within request.todo the whole found.
- Should not be able to put user and todo in request when user does not exists
  - For this test to pass, in checksTodoExists middleware you must return a response with status 404 if there is no user with the username passed in the request header.
- Should not be able to put user and todo in request when todo id is not uuid
  - To pass this test, the middleware checksTodoExists you must return a response with status 400 if the id of all passed through the request parameters is not a valid UUID (eg 1234abcd ).
- Should not be able to put user and todo in request when todo does not exists
  - To pass this test, the middleware checksTodoExists you must return a response with status 404 if the id of all passed through the parameters of the request does not belong to any all user found.
- Should be able to find user by id route param and pass it to request.user
  - For this test to pass, the findUserById middleware must receive a user id from within request.params . You must validate that the user exists, pass it on to request.user and return the next function call.
- Should not be able to pass user to request.user when it does not exists
  - For this test to pass, in the findUserById middleware you must return a response with status 404 if the user id passed by the request parameters does not belong to any registered user.
    All other tests are the same tests found in challenge 01 with some (or no) changes.
    It is worth emphasizing that this challenge is focused only on middlewares and you do not need to modify the route content for the tests to pass

## Delivery

This challenge must be delivered from the Rocketseat platform. Submit the link to the repository where you made your changes. After completing the challenge, in addition to sending the code to GitHub, making a post on LinkedIn is a good way to demonstrate your knowledge and efforts to evolve your career for future opportunities.
Made with by Rocketseat Join our open community!

[Original description](https://www.notion.so/Desafio-02-Trabalhando-com-middlewares-4f89bf538c2e4ee291382b92bdc36790#5d5ddeb654924be5b72cd8951b5411bf)
