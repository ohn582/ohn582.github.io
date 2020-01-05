---
layout: post
title:      "Flatiron: MOD 3 JAVASCRIPT PROJECT"
date:       2020-01-05 20:22:28 +0000
permalink:  flatiron_mod_3_javascript_project
---



For this project, my app focuses on creating a simple electronics review app. I have two models from the backend, both of them are “reviews” and “electronics”. “Electronics” focuses on showing the list of items such as GPS, Consoles, Computers, etc. that will allow the users to select a certain item to show that specific info such as image, description, and title. For the other model, theirs “review” that model, is for the public reviews where the users can post more than one comment about that specific item(electronics has many reviews & reviews belongs to electronics). 


In this project, what I enjoy the most creating CSS codes. I this code I want my buttons to change colors every time I hover my mouse over the button. To make it work, I use '(className:hover)' in css that will allow the mouse to create an effect.



The hardest part in this project was at the end of this project. At the end of the project, I was trying to create three different methods such as ‘POST’, ‘DELETE’, and ‘PATCH’. When I was testing the code, it managed to make it work, but not the way I wanted. I believe the problem was that all of my methods are in one class together. The method for post is working fine, but the other two was having issues. Every time i tried to press a delete button, it automatically creates another review, that says undefined, as I refreshed the app, it finally disappeared the comment. Same for the patch method, it's exactly the same thing, every time I select the edit button it keeps creating the new comment saying undefined. In order for me to resolve this problem, I've created a 'div' with an id for 'userComment.innerHTML' because it doesn't have it's own separate comment id. Another problem that I fixed was having the post paste to the other class allowing the buttons both delete and edit to work properly. For the post method, the problem was that my variable is connected to the wrong attribute.
