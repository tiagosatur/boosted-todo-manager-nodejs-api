# boosted-todo-manager-nodejs-api

<div class="notion-page-content" style="flex-shrink: 0; flex-grow: 1; width: 900px; max-width: 100%; display: flex; align-items: center; flex-direction: column; font-size: 16px; line-height: 1.5; padding-left: calc(96px + env(safe-area-inset-left)); padding-right: calc(96px + env(safe-area-inset-right)); padding-bottom: 30vh;">
 <div data-block-id="daa5ffe5-e813-44cd-a15d-8ec2d201f6e6" class="notion-selectable notion-header-block" style="width: 100%; max-width: 1250px; margin-top: 2em; margin-bottom: 4px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.875em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 1" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span>About this challenge</span></div>
    </div>
 </div>
 <div data-block-id="46a068dd-8990-47fe-87c1-a85ab22d9e01" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In this challenge you will work more deeply with middlewares in Express. </font><font style="vertical-align: inherit;">That way you will be able to further secure the knowledge gained so far.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="012ac048-6c95-4d8a-b0b7-00a455e768e0" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">To make the business rule a little easier, you'll work with the same application from the previous challenge: an application to manage tasks (or </font></font></span><span style="font-style:italic" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ) but with some changes.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="8a2eb8f2-76ce-4e93-8c83-78ddbb31fe2f" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">It will be allowed to create a user with&nbsp; </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="1" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">name</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &nbsp;and&nbsp; </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">username</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> , as well as to CRUD&nbsp; </font></font></span><span style="font-style:italic" data-token-index="5"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> :</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="df3c5f67-11cd-43b1-8e60-c7bfb9b9b799" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Create a new </font></font></span><span style="font-style:italic" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ;</font></font></span></div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="7565274d-2c6a-4be8-96c7-56868f73ab65" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">List all </font></font></span><span style="font-style:italic" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ;</font></font></span></div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="9f5211df-2b99-49bd-821c-f0e03e3673a9" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Change the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="1" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">title</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> and </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">deadline</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> of an </font></font></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;">existing </font></span></font><span style="font-style:italic" data-token-index="5"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ;</font></font></span></div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="033d9922-41c1-4b76-a342-6151278ecfb5" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mark a </font></font></span><span style="font-style:italic" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> as done;</font></font></span></div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="c8cc846c-f78d-4c2d-bf89-e5b0ea46603b" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Delete a </font></font></span><span style="font-style:italic" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ;</font></font></span></div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="754d352e-ec35-45aa-88f0-e2cfe3b6e9c5" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">All of this for each specific user. </font><font style="vertical-align: inherit;">In addition, this time we will have a free plan where the user can only create up to ten </font></font></span><span style="font-style:italic" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> and a Pro plan that will allow you to create </font></font></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;">unlimited </font></span></font><span style="font-style:italic" data-token-index="3"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> , all this using middleware to make the necessary validations.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="dada1139-c47e-454a-a2c7-d51d82d4d49d" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">We'll look in more detail below at what needs to be done and how </font></font><img class="notion-emoji" alt="🚀" aria-label="🚀" style="width:1em;height:1em;background-repeat:no-repeat;background:url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;);background-position-x:58.92857142857143%;background-position-y:100%;background-size:5700% 5700%;vertical-align:-0.1em;margin:0 0.1em" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="25b7be8d-feec-4966-ad47-3792c247545b" class="notion-selectable notion-sub_header-block" style="width: 100%; max-width: 1250px; margin-top: 1.4em; margin-bottom: 1px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.5em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 2" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Application template</font></font></span></div>
    </div>
 </div>
 <div data-block-id="7feb747c-7dbd-418e-9d00-d98164b6a0e2" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">To help you with this challenge, we've created this template for you that you should use as a GitHub template.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="03f39d49-c54f-4d4e-bf2c-1fd8ce961925" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The template is available at the following URL: </font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="b5494a79-7fc0-49f2-82c2-febbe2fad089" class="notion-selectable notion-bookmark-block" style="width: 100%; max-width: 1250px; margin-top: 4px; margin-bottom: 4px;">
    <div>
       <div style="display: flex;">
          <a target="_blank" rel="noopener noreferrer" style="display: block; color: inherit; text-decoration: none; flex-grow: 1; min-width: 0px;" href="https://github.com/rocketseat-education/ignite-template-trabalhando-com-middlewares">
             <div class="notion-focusable" role="button" tabindex="-1" style="user-select: none; transition: background 20ms ease-in 0s; cursor: pointer; width: 100%; display: flex; flex-wrap: wrap-reverse; align-items: stretch; text-align: left; overflow: hidden; border: 1px solid rgba(55, 53, 47, 0.16); border-radius: 3px; position: relative; color: inherit; fill: inherit;">
                <div style="flex: 4 1 180px; padding: 12px 14px 14px; overflow: hidden; text-align: left;">
                   <div style="font-size: 14px; line-height: 20px; color: rgb(55, 53, 47); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; min-height: 24px; margin-bottom: 2px;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rocketseat-education/ignite-template-working-with-middlewares</font></font></div>
                   <div style="font-size: 12px; line-height: 16px; color: rgba(55, 53, 47, 0.6); height: 32px; overflow: hidden;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ignite] Challenge 02 - Node.js Track. </font><font style="vertical-align: inherit;">Contribute to rocketseat-education/ignite-template-working-with-middlewares development by creating an account on GitHub.</font></font></div>
                   <div style="display: flex; margin-top: 6px;">
                      <img src="/image/https%3A%2F%2Fgithub.com%2Ffavicon.ico?table=block&amp;id=b5494a79-7fc0-49f2-82c2-febbe2fad089&amp;spaceId=08f749ff-d06d-49a8-a488-9846e081b224&amp;userId=c80a2386-d824-4419-b36c-3a96accb76ac&amp;cache=v2" style="width: 16px; height: 16px; min-width: 16px; margin-right: 6px;">
                      <div style="font-size: 12px; line-height: 16px; color: rgb(55, 53, 47); white-space: nowrap; overflow: hidden; text-overflow: ellipsis;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/rocketseat-education/ignite-template-trabalhando-com-middlewares</font></font></div>
                   </div>
                </div>
                <div style="flex: 1 1 180px; display: block; position: relative;">
                   <div style="position: absolute; inset: 0px;">
                      <div style="width: 100%; height: 100%;"><img src="https://repository-images.githubusercontent.com/344544085/4f140700-8000-11eb-9bed-82742b142698" style="display: block; object-fit: cover; border-radius: 1px; width: 100%; height: 100%;"></div>
                   </div>
                </div>
             </div>
          </a>
       </div>
    </div>
 </div>
 <div data-block-id="2436a4fc-391c-4ef2-bbb8-98b7b6393825" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span style="font-weight:600" data-token-index="0"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tip</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : If you don't know how to use GitHub repositories as a template, we have a guide in </font></font></span><a href="/ddd8fcdf2339436a816a0d9e45767664" style="cursor:pointer;color:inherit;word-wrap:break-word;font-weight:500;text-decoration:inherit" class="notion-link-token notion-enable-hover" target="_blank" rel="noopener noreferrer" data-token-index="2"><span style="border-bottom:0.05em solid;border-color:rgba(55,53,47,0.4);opacity:0.7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">our FAQ</font></font></span></span></a><span style="font-weight:600" data-token-index="3"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> .</font></font></span></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="78988ff5-da21-4866-ac9d-2b99650f1b6c" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Now navigate to the created folder, open it in Visual Studio Code and finally open the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="1" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">index.js</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> file </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">Remember to run the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">yarn</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> command </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">on your terminal to install all dependencies and you will have the following code:</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="bff639fa-4de8-4d5f-82ea-7b2f5dc03029" class="notion-selectable notion-image-block" style="width: 100%; max-width: 1442px; align-self: center; margin-top: 0.5em; margin-bottom: 0.5em;">
    <div>
       <div style="display: flex;">
          <div class="notion-cursor-default" style="position: relative; overflow: hidden; flex-grow: 1;">
             <div style="position: relative;">
                <div style="height: 100%; width: 100%;"><img style="display: block; object-fit: cover; border-radius: 1px; width: 100%; pointer-events: auto;" src="https://i.imgur.com/xRNTZRw.png"></div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="5a9e5bf7-adbe-49cb-98e0-4632d43b34de" class="notion-selectable notion-sub_header-block" style="width: 100%; max-width: 1250px; margin-top: 1.4em; margin-bottom: 1px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.5em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 2" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Application Middlewares</font></font></span></div>
    </div>
 </div>
 <div data-block-id="a2ef0591-794e-4721-872c-ff3b475f0346" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">With the template already cloned and the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="1" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">index.js</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> file </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">open, you must complete where there is no code with the code to achieve the objectives of each test.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="928d3164-a56a-4339-8699-654e25e6dfc6" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In this challenge it will not be necessary to change the code of any route, </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">only the middlewares</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> . </font><font style="vertical-align: inherit;">The tests will also test the operation of the routes but the result depends only on the middlewares.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="f6e6da71-4769-4a2d-89b2-9625c1089f45" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Here we will have a brief description of what each middleware should do and in </font></font></span><a href="/4f89bf538c2e4ee291382b92bdc36790#1ac72354b1184b389a1640ff1a87955e" style="cursor:pointer;color:inherit;word-wrap:break-word;font-weight:500;text-decoration:inherit" class="notion-link-token notion-enable-hover" target="_blank" rel="noopener noreferrer" data-token-index="1"><span style="border-bottom:0.05em solid;border-color:rgba(55,53,47,0.4);opacity:0.7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">the Test specification</font></font></span></span></a><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> section </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">you will see in more detail what needs to be done to satisfy each test.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="5d5ddeb6-5492-4be5-b72c-d8951b5411bf" class="notion-selectable notion-sub_sub_header-block" style="width: 100%; max-width: 1250px; margin-top: 1em; margin-bottom: 1px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.25em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 3" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span>checksExistsUserAccount</span></div>
    </div>
 </div>
 <div data-block-id="3cca1f65-c36c-4be8-a534-1a19ab9d2cbf" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">This middleware is responsible for receiving the username of the user by the header and validating whether or not there is a user with the username passed. </font><font style="vertical-align: inherit;">If it exists, the user must be transferred to the request and the next function must be called.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="aeff0510-17e5-4c94-8648-beca2f281d9d" class="notion-selectable notion-sub_sub_header-block" style="width: 100%; max-width: 1250px; margin-top: 1em; margin-bottom: 1px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.25em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 3" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span>checksCreateTodosUserAvailability</span></div>
    </div>
 </div>
 <div data-block-id="a868bd2b-4232-456c-b980-ef39facd8024" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">This middleware must receive the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">user</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> already inside the request and call the function next only if this user is still in </font></font></span><span style="font-weight:600" data-token-index="3"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">the free plan and does not have 10 </font></font></span></span><span style="font-style:italic;font-weight:600" data-token-index="4"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all </font></font></span></span><span style="font-weight:600" data-token-index="5"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">registered</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> or if he </font></font></span><span style="font-weight:600" data-token-index="7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">already has the Pro plan activated</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> .</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="929d6beb-e43c-4d6e-a6c6-1ff13a42729b" class="notion-selectable notion-sub_sub_header-block" style="width: 100%; max-width: 1250px; margin-top: 1em; margin-bottom: 1px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.25em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 3" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span>checksTodoExists</span></div>
    </div>
 </div>
 <div data-block-id="5a1eb046-e906-4082-a571-164043d12fa3" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">This middleware must receive the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">username</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> from within the header and the </font></font></span><span style="font-weight:600" data-token-index="3"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> of a </font></font></span><span style="font-style:italic" data-token-index="5"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> from within </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="7" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request.params</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> . </font><font style="vertical-align: inherit;">You must validate the user, validate that the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="9" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> is a uuid and also validate that this </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="11" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> belongs to a </font></font></span><span style="font-style:italic" data-token-index="13"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> of the informed user.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="a208d80e-f867-44d0-9f1f-7df3cfa13edd" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">With all validations passing, the </font></font></span><span style="font-style:italic" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> found must be passed to the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> as well as the user found as well and the next function must be called.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="e5d855b9-2be9-45f4-9bcf-3120980edc51" class="notion-selectable notion-sub_sub_header-block" style="width: 100%; max-width: 1250px; margin-top: 1em; margin-bottom: 1px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.25em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 3" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">findUserById</font></font></span></div>
    </div>
 </div>
 <div data-block-id="4dc38aca-a5d0-4238-a27f-922e84e5c6d3" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">This middleware has a similar operation to the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="1" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksExistsUserAccount</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware, </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">but the search for the user must be done through </font></font></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;">a user </font></span></font><span style="font-weight:600" data-token-index="3"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> passed by a parameter in the route. </font><font style="vertical-align: inherit;">If the user has been found, it must be passed into </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request.user</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> and the next function must be called.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="1ac72354-b118-4b38-9a16-40ff1a87955e" class="notion-selectable notion-sub_header-block" style="width: 100%; max-width: 1250px; margin-top: 1.4em; margin-bottom: 1px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.5em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 2" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Test Specification</font></font></span></div>
    </div>
 </div>
 <div data-block-id="e4a62a37-7306-4df1-95ab-a1ad61283d29" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In each test, you have a brief description of what your application must do for the test to pass.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="5ca86c1a-66e8-4bdb-8a14-4a84576e847f" class="notion-selectable notion-callout-block" style="width: 100%; max-width: 1250px; margin-top: 4px; margin-bottom: 4px;">
    <div style="display: flex;">
       <div style="padding: 16px 16px 16px 12px; display: flex; width: 100%; border-radius: 3px; border-width: 1px; border-style: solid; border-color: transparent; background: rgba(235, 236, 237, 0.3);">
          <div>
             <div class="notion-record-icon notranslate notion-focusable" role="button" aria-disabled="true" tabindex="-1" style="user-select: none; transition: background 20ms ease-in 0s; display: flex; align-items: center; justify-content: center; height: 24px; width: 24px; border-radius: 3px; flex-shrink: 0;">
                <div style="display: flex; align-items: center; justify-content: center; height: 24px; width: 24px;">
                   <div style="height: 16.8px; width: 16.8px; font-size: 16.8px; line-height: 1.1; margin-left: 0px; color: black;"><img class="notion-emoji" alt="💡" aria-label="💡" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==" style="width: 100%; height: 100%; background: url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;) 44.6429% 76.7857% / 5700% 5700%;"></div>
                </div>
             </div>
          </div>
          <div contenteditable="false" spellcheck="true" placeholder="Type something…" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); margin-left: 8px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">If you have questions about what the tests are, and how to interpret them, take a look at&nbsp; </font></font></span><a href="/ddd8fcdf2339436a816a0d9e45767664" style="cursor:pointer;color:inherit;word-wrap:break-word;font-weight:500;text-decoration:inherit" class="notion-link-token notion-enable-hover" target="_blank" rel="noopener noreferrer" data-token-index="1"><span style="border-bottom:0.05em solid;border-color:rgba(55,53,47,0.4);opacity:0.7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">our FAQ</font></font></span></span></a></div>
       </div>
    </div>
 </div>
 <div data-block-id="c3e94316-522d-4b2f-9cac-c543e06750ee" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this challenge, we have the following tests:</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="e3510e3c-3781-4930-8e8f-a3542d8efd97" class="notion-selectable notion-sub_sub_header-block" style="width: 100%; max-width: 1250px; margin-top: 1em; margin-bottom: 1px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.25em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 3" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Middleware tests</font></font></span></div>
    </div>
 </div>
 <div data-block-id="b0a4b58d-a265-481d-b40f-41a1f43fa95e" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should be able to find user by username in header and pass it to request.user</span></span></div>
          </div>
          <div data-block-id="1d419d2d-18ab-47fe-a0e3-2bc09dee5b9f" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 1px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, you must allow the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksExistsUserAccount</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware to </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">receive a username through the request header and if a user with the same username exists, it must be placed inside </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request.user</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> and, at the end, return the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">next</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> function call. </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></span></div>
                </div>
             </div>
          </div>
          <div data-block-id="192dc550-afad-4ebd-b681-ddfb244a5bcd" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 1px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pay attention to the name of the property that will store the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="1" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">user</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> object </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">in the request.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="08962723-525e-49dc-946f-b5134a1260b2" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should not be able to find a non existing user by username in header</span></span></div>
          </div>
          <div data-block-id="7cd7f541-2dc1-4659-96c4-5177c185f675" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, in the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksExistsUserAccount</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">you must return a response with status </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">404</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> if the username passed in the request header does not belong to any user. </font><font style="vertical-align: inherit;">You can also return an error message, but this is optional.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="0daf326a-878a-4804-9883-2ec6a8cd6ca5" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should be able to let user create a new todo when is in free plan and have less than ten todos</span></span></div>
          </div>
          <div data-block-id="e9d11e80-6b02-4ec2-b063-dde18df4b0f1" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 1px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, you must allow the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksCreateTodosUserAvailability</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware to </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">receive the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">user</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> object </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(consider whenever the object exists) from the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> and call the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="7" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">next</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> function </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">only in case the user is in </font></font></span><span style="font-weight:600" data-token-index="9"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">the free plan and does not have 10 </font></font></span></span><span style="font-style:italic;font-weight:600" data-token-index="10"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all </font></font></span></span><span style="font-weight:600" data-token-index="11"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">registered</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> or if he </font></font></span><span style="font-weight:600" data-token-index="13"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">already has the Pro plan activated</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> .</font></font></span></div>
                </div>
             </div>
          </div>
          <div data-block-id="543bb3ed-60a8-4bc1-aefb-7b46895cc21d" class="notion-selectable notion-callout-block" style="width: 100%; max-width: 100%; margin-top: 4px; margin-bottom: 0px;">
             <div style="display: flex;">
                <div style="padding: 16px 16px 16px 12px; display: flex; width: 100%; border-radius: 3px; border-width: 1px; border-style: solid; border-color: transparent; background: rgba(235, 236, 237, 0.3);">
                   <div>
                      <div class="notion-record-icon notranslate notion-focusable" role="button" aria-disabled="true" tabindex="-1" style="user-select: none; transition: background 20ms ease-in 0s; display: flex; align-items: center; justify-content: center; height: 24px; width: 24px; border-radius: 3px; flex-shrink: 0;">
                         <div style="display: flex; align-items: center; justify-content: center; height: 24px; width: 24px;">
                            <div style="height: 16.8px; width: 16.8px; font-size: 16.8px; line-height: 1.1; margin-left: 0px; color: black;"><img class="notion-emoji" alt="💡" aria-label="💡" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==" style="width: 100%; height: 100%; background: url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;) 44.6429% 76.7857% / 5700% 5700%;"></div>
                         </div>
                      </div>
                   </div>
                   <div contenteditable="false" spellcheck="true" placeholder="Type something…" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); margin-left: 8px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">You can check whether the user has a Pro plan or not from the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="1" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">user.pro</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> property </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">If it is </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">true it</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> means that the Pro plan is in use.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="cf7aaa39-dd6c-4316-afc3-035357221c07" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should not be able to let user create a new todo when is not Pro and already have ten todos</span></span></div>
          </div>
          <div data-block-id="e2e978bc-dc89-4db1-9280-ba4bfe34327c" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, in the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksCreateTodosUserAvailability</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">you must return a response with status </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">403</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> if the user received by the request is in </font></font></span><span style="font-weight:600" data-token-index="5"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">the free plan</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> and </font></font></span><span style="font-weight:600" data-token-index="7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">has already 10 </font></font></span></span><span style="font-style:italic;font-weight:600" data-token-index="8"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all </font></font></span></span><span style="font-weight:600" data-token-index="9"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">registered</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> . </font><font style="vertical-align: inherit;">You can also return an error message, but this is optional.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="e0fb6b2b-67f7-4a39-a423-2529542e45bb" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should be able to let user create infinite new todos when is in Pro plan</span></span></div>
          </div>
          <div data-block-id="f3493f13-8aa1-4ae2-8274-3858e6e39b5f" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 1px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, you must allow the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksCreateTodosUserAvailability</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware to </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">receive the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">user</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> object </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(consider whenever the object exists) from the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> and call the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="7" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">next</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> function </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">if the user already has the Pro plan.</font></font></span></div>
                </div>
             </div>
          </div>
          <div data-block-id="ce047dd3-6bcb-48e0-b1ff-defc357379bc" class="notion-selectable notion-callout-block" style="width: 100%; max-width: 100%; margin-top: 4px; margin-bottom: 0px;">
             <div style="display: flex;">
                <div style="padding: 16px 16px 16px 12px; display: flex; width: 100%; border-radius: 3px; border-width: 1px; border-style: solid; border-color: transparent; background: rgba(235, 236, 237, 0.3);">
                   <div>
                      <div class="notion-record-icon notranslate notion-focusable" role="button" aria-disabled="true" tabindex="-1" style="user-select: none; transition: background 20ms ease-in 0s; display: flex; align-items: center; justify-content: center; height: 24px; width: 24px; border-radius: 3px; flex-shrink: 0;">
                         <div style="display: flex; align-items: center; justify-content: center; height: 24px; width: 24px;">
                            <div style="height: 16.8px; width: 16.8px; font-size: 16.8px; line-height: 1.1; margin-left: 0px; color: black;"><img class="notion-emoji" alt="💡" aria-label="💡" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==" style="width: 100%; height: 100%; background: url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;) 44.6429% 76.7857% / 5700% 5700%;"></div>
                         </div>
                      </div>
                   </div>
                   <div contenteditable="false" spellcheck="true" placeholder="Type something…" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); margin-left: 8px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">If you passed the two previous tests before this one, it should already pass too.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="c40230e7-cd2f-4064-8cbf-57478d0828c1" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should be able to put user and todo in request when both exits</span></span></div>
          </div>
          <div data-block-id="f824ee5b-084b-4766-b588-f49ee84de5df" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 1px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksTodoExists</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">must receive the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">username</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> from within the header and the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> of a </font></font></span><span style="font-style:italic" data-token-index="7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> from within </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="9" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request.params</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> . </font><font style="vertical-align: inherit;">You must validate that the user exists, validate that the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="11" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> is a uuid and also validate that this </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="13" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> belongs to a </font></font></span><span style="font-style:italic" data-token-index="15"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> of the informed user.</font></font></span></div>
                </div>
             </div>
          </div>
          <div data-block-id="fc05f0dd-6a8b-4a83-b757-97e3a43c715b" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 1px; margin-bottom: 1px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">With all validations passing, the </font></font></span><span style="font-style:italic" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> found must be passed to the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> as well as the user found as well and the next function must be called.</font></font></span></div>
                </div>
             </div>
          </div>
          <div data-block-id="314d4c90-4975-4ede-8127-c9296f46f5cc" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 1px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">It is important that you put in </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="1" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request.user</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> the user found and within </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request.todo</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> the </font></font></span><span style="font-style:italic" data-token-index="5"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">whole</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> found.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="88fbb14f-96cf-46e2-b474-bacfe2e72f50" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should not be able to put user and todo in request when user does not exists</span></span></div>
          </div>
          <div data-block-id="ddb18355-c6fe-41a7-ab31-6f5b7078bbf9" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, in </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksTodoExists</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">you must return a response with status </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">404</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> if there is no user with the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">username</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> passed in the request header.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="c0ef7228-4f17-4450-9122-401a3a551ca8" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should not be able to put user and todo in request when todo id is not uuid</span></span></div>
          </div>
          <div data-block-id="0da30b62-e5e7-4cc8-9dff-17356e69fda3" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">To pass this test, the middleware </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksTodoExists</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> you must return a response with status </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">400</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> if the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> of </font></font></span><span style="font-style:italic" data-token-index="7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> passed through the request parameters is not a valid UUID (eg </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="9" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1234abcd</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ).</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="adbbea98-21db-4131-8a37-ecd42b3e27ed" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should not be able to put user and todo in request when todo does not exists</span></span></div>
          </div>
          <div data-block-id="2110fed5-ccbb-43ca-a71f-8e396dcb88d8" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">To pass this test, the middleware </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">checksTodoExists</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> you must return a response with status </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">404</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> if the </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> of </font></font></span><span style="font-style:italic" data-token-index="7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> passed through the parameters of the request does not belong to any </font></font></span><span style="font-style:italic" data-token-index="9"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">all</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> user found.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="2bba5674-12eb-4960-a56b-293538f93b8e" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should be able to find user by id route param and pass it to request.user</span></span></div>
          </div>
          <div data-block-id="add4ce59-60f4-4c7a-8904-d325ff3a7b65" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">findUserById</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">must receive </font></font></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;">a user </font></span></font><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> from within </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request.params</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> . </font><font style="vertical-align: inherit;">You must validate that the user exists, pass it on to </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="7" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">request.user</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> and return the next function call.</font></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="2c30c98d-c971-4d47-8f12-1b644e536eb1" class="notion-selectable notion-bulleted_list-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="display: flex; align-items: flex-start; width: 100%; padding-left: 2px; color: inherit; fill: inherit;">
       <div style="margin-right: 2px; width: 24px; display: flex; align-items: center; justify-content: center; flex-grow: 0; flex-shrink: 0; min-height: calc(1.5em + 3px + 3px);">
          <div style="font-size: 1.5em; line-height: 1; margin-bottom: 0.1em;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">•</font></font></div>
       </div>
       <div style="flex: 1 1 0px; min-width: 1px; display: flex; flex-direction: column;">
          <div style="display: flex;">
             <div contenteditable="false" spellcheck="true" placeholder="List" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; text-align: left;"><span style="font-weight:600" data-token-index="0"><span>Should not be able to pass user to request.user when it does not exists</span></span></div>
          </div>
          <div data-block-id="c391b575-f23d-4610-be60-adaaa7a11d79" class="notion-selectable notion-text-block" style="width: 100%; max-width: 100%; margin-top: 2px; margin-bottom: 0px;">
             <div style="color: inherit; fill: inherit;">
                <div style="display: flex;">
                   <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For this test to pass, in the </font></font></span><span style="font-weight:600" data-token-index="1"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">findUserById</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> middleware </font></span></font><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">you must return a response with status </font></font></span><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="3" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">404</font></font></span></span><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> if the </font></font></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;">user </font></span></font><span style="font-family:&quot;SFMono-Regular&quot;, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace;line-height:normal;background:rgba(135,131,120,0.15);color:#EB5757;border-radius:3px;font-size:85%;padding:0.2em 0.4em" data-token-index="5" spellcheck="false"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></span></span><font style="vertical-align: inherit;"><span><font style="vertical-align: inherit;"> passed by the request parameters does not belong to any registered user.</font></span></font><span><font style="vertical-align: inherit;"></font></span><span style="font-style:italic" data-token-index="7"><span> </span></span><span><font style="vertical-align: inherit;"></font></span></div>
                </div>
             </div>
          </div>
       </div>
    </div>
 </div>
 <div data-block-id="aafef43b-29e2-40c2-8d61-8791fdef9199" class="notion-selectable notion-divider-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div class="notion-cursor-default" style="display: flex; align-items: center; justify-content: center; pointer-events: auto; width: 100%; height: 13px; flex: 0 0 auto; color: rgb(228, 227, 226);">
       <div style="width: 100%; height: 1px; visibility: visible; border-bottom: 1px solid rgba(55, 53, 47, 0.09);"></div>
    </div>
 </div>
 <div data-block-id="20929494-b4da-47f8-8ce9-7a0e6da598f0" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">All other tests are the same tests found in challenge 01 with some (or no) changes.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="bd129649-1bb0-43e3-add3-8343281113f2" class="notion-selectable notion-callout-block" style="width: 100%; max-width: 1250px; margin-top: 4px; margin-bottom: 4px;">
    <div style="display: flex;">
       <div style="padding: 16px 16px 16px 12px; display: flex; width: 100%; border-radius: 3px; border-width: 1px; border-style: solid; border-color: transparent; background: rgba(235, 236, 237, 0.3);">
          <div>
             <div class="notion-record-icon notranslate notion-focusable" role="button" aria-disabled="true" tabindex="-1" style="user-select: none; transition: background 20ms ease-in 0s; display: flex; align-items: center; justify-content: center; height: 24px; width: 24px; border-radius: 3px; flex-shrink: 0;">
                <div style="display: flex; align-items: center; justify-content: center; height: 24px; width: 24px;">
                   <div style="height: 16.8px; width: 16.8px; font-size: 16.8px; line-height: 1.1; margin-left: 0px; color: black;"><img class="notion-emoji" alt="⚠️" aria-label="⚠️" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==" style="width: 100%; height: 100%; background: url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;) 94.6429% 89.2857% / 5700% 5700%;"></div>
                </div>
             </div>
          </div>
          <div contenteditable="false" spellcheck="true" placeholder="Type something…" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); margin-left: 8px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> It is worth emphasizing that this challenge is focused only on middlewares and you do not need to modify the route content for the tests to pass </font></font><img class="notion-emoji" alt="💜" aria-label="💜" style="width:1em;height:1em;background-repeat:no-repeat;background:url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;);background-position-x:44.642857142857146%;background-position-y:67.85714285714286%;background-size:5700% 5700%;vertical-align:-0.1em;margin:0 0.1em" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="198a5e3c-d65e-4f6e-9fd4-3775d0a3a9d0" class="notion-selectable notion-header-block" style="width: 100%; max-width: 1250px; margin-top: 2em; margin-bottom: 4px;">
    <div style="display: flex; width: 100%; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, &quot;Apple Color Emoji&quot;, Arial, sans-serif, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-weight: 600; font-size: 1.875em; line-height: 1.3; color: inherit; fill: inherit;">
       <div contenteditable="false" spellcheck="true" placeholder="Heading 1" data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><img class="notion-emoji" alt="📅" aria-label="📅" style="width:1em;height:1em;background-repeat:no-repeat;background:url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;);background-position-x:46.42857142857143%;background-position-y:48.214285714285715%;background-size:5700% 5700%;vertical-align:-0.1em;margin:0 0.1em" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Delivery</font></font></span></div>
    </div>
 </div>
 <div data-block-id="183baf4a-dfb4-4f7a-aca9-9c1f247b8358" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">This challenge must be delivered from the Rocketseat platform. </font><font style="vertical-align: inherit;">Submit the link to the repository where you made your changes. </font><font style="vertical-align: inherit;">After completing the challenge, in addition to sending the code to GitHub, making a post on LinkedIn is a good way to demonstrate your knowledge and efforts to evolve your career for future opportunities.</font></font></span></div>
       </div>
    </div>
 </div>
 <div data-block-id="3d52fd63-2c63-42a6-8b34-546ae3435f13" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; min-height: 1em; color: rgb(55, 53, 47); -webkit-text-fill-color: rgba(55, 53, 47, 0.4);"></div>
       </div>
    </div>
 </div>
 <div data-block-id="897709c8-2f85-4b4b-89ab-9365e32d2260" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 1px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px;"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Made with </font></font><img class="notion-emoji" alt="💜" aria-label="💜" style="width:1em;height:1em;background-repeat:no-repeat;background:url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;);background-position-x:44.642857142857146%;background-position-y:67.85714285714286%;background-size:5700% 5700%;vertical-align:-0.1em;margin:0 0.1em" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">by Rocketseat </font></font><img class="notion-emoji" alt="👋" aria-label="👋" style="width:1em;height:1em;background-repeat:no-repeat;background:url(&quot;/images/twitter-emoji-spritesheet-64.png&quot;);background-position-x:23.214285714285715%;background-position-y:46.42857142857143%;background-size:5700% 5700%;vertical-align:-0.1em;margin:0 0.1em" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Join our </font></font></span><a href="https://discord.gg/pUU3CG4Z" style="cursor:pointer;color:inherit;word-wrap:break-word;text-decoration:inherit" class="notion-link-token notion-enable-hover" target="_blank" rel="noopener noreferrer" data-token-index="1"><span style="border-bottom:0.05em solid;border-color:rgba(55,53,47,0.4);opacity:0.7"><span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">open community!</font></font></span></span></a></div>
       </div>
    </div>
 </div>
 <div data-block-id="a91ebd92-d812-4448-aee0-24806e17d528" class="notion-selectable notion-text-block" style="width: 100%; max-width: 1250px; margin-top: 1px; margin-bottom: 0px;">
    <div style="color: inherit; fill: inherit;">
       <div style="display: flex;">
          <div contenteditable="false" spellcheck="true" placeholder=" " data-root="true" class="" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding: 3px 2px; min-height: 1em; color: rgb(55, 53, 47); -webkit-text-fill-color: rgba(55, 53, 47, 0.4);"></div>
       </div>
    </div>
 </div>
</div>

[Original description](https://www.notion.so/Desafio-02-Trabalhando-com-middlewares-4f89bf538c2e4ee291382b92bdc36790#5d5ddeb654924be5b72cd8951b5411bf)
