---
layout: post
title:      "Creating Issuses with CRUD"
date:       2020-01-05 15:20:07 -0500
permalink:  mod_3_javascript_project
---



CRUD stands or represent four basic functions create, read, update, destroy. CRUD is used when you are creating or editing an spacific object. However, it could be troubbling sometimes, for example lets just say you want to post a comment using the post method, to make this work, the method post heeds to have a addevent listner. Addevent listner has two diffrent arguments, one is listining to the event (ex: 'click' or 'submit') and the other one is call back. For this situation, since we are creating a post method, our event listner has to have submit because we are creating in a class form (Submit is only used when you are using a form).

```
   let submitButton = document.querySelector(".user-comment")
        submitButton.addEventListener('submit', (evt) => {

            evt.preventDefault() <--Important when you are working on a form
        })
```

```
            <form class="user-comment">
            </form>
```

Once you created the event listener, you always need to have 'preventDefault()' this prevents the web from refresshing it when you submit a comment. After creating prevent defult, you must write a proper fetch url, it's an easy way to  fetch resources across the network. Then you should an open and closed curly bracket for both method and headers. Create 'body: JSON.stringify({.......})',

```
         fetch(`http://localhost:3000/reviews`, {
                method: "POST",
                headers: {
                    'Content-Type': 'application/json',
                    'Accept': 'application/json'
                },
                body: JSON.stringify({
                    name: commentInfo.name.value,
                    content: commentInfo.comment.value,
                    eletronic_id: commentInfo.id
                })
        })
```
