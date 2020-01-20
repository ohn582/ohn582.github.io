---
layout: post
title:      "Lags & bug issues in JavaScript"
date:       2020-01-20 18:05:01 -0500
permalink:  lags_and_bug_issues_in_javascript
---


Bugs and lags are a nigtmare for javascript such as long rendering/loading time. For example, I want to submit a comment, however, it's not responding, it takes a long time to recive the comment. Another issue is every time you tried to refresh your web, it takes at least a minute to return to the home page. Their multiple cause for this to happend, one is you have too many addevent listners every time when you clicked , another problem is that once your console started loading while refreshing the web, it going to take a little bit longer, to fix that problem, you must use control + c to shut off the surver. To fix this problem, try to reset your seeds, for example, make sure you use "rails db:rollback" in your console, this allows your controller to be pulled down 
