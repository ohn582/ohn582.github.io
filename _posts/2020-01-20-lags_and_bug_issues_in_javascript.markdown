---
layout: post
title:      "Lags & bug issues in JavaScript"
date:       2020-01-20 18:05:01 -0500
permalink:  lags_and_bug_issues_in_javascript
---


Bugs and lags are a nigtmare for javascript such as long rendering/loading time. For example, I want to submit a comment, however, it's not responding, it takes a long time to recive the comment. Another issue is every time you tried to refresh your web, it takes at least a minute to return to the home page. Their multiple cause for this to happend, one is you have too many addevent listners every time when you clicked , another problem is that once your console started loading while refreshing the web, it going to take a little bit longer, to fix that problem, you must use control + c to shut off the surver. To fix this problem, try to reset your seeds, for example, make sure you use "rails db:rollback" in your console, this allows your controller to be pulled down from your schema file (this one way to reset your seed data) this helps when you have too many seed data that was created from your data. Another way is to check your post method weather or not if you are creating a multiple method in one form, that's also another problem when you are colliding multiple objects.

When you building project and you relize that some of your text or buttons can be missing since you wrote down all of you code properly without any errors or misspled variable, this is a very rare problem, the cause was that your rails backend controller is not setup properly. To fix this problem, you can go to the console and type "rails d 'name of your controller' 'name of your string or integer' " to delete your controller and re-write it again. NOTE: when you are using the console to generate a file, 'g' represents generate (create a file), and 'd' means to delete a file. After finishing generating your file, use 'rails db:migrate' to create a schema and to test out your web to see if your code is working properly.
