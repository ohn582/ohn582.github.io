---
layout: post
title:      "Fatal Error/Buggy Codes: Making simple mistakes"
date:       2020-03-24 12:54:09 -0400
permalink:  fatal_error_buggy_codes_making_simple_mistakes
---


During my mod 2, making small mistakes such as Plurals & and spelling errors are important and one of the most common issues that I have encounter through this model including my previous model. I know what you are thinking plurals aren’t that bad or not that hard to use and spelling is just a small thing, your wrong. As a programmer, when you are trying to build a complex application or when you keep rushing through your code, it becomes a little bit annoying and you have to go back and fix it on what or where you want to fix your errors. For example, in my mod 2 class, I was creating my project using a many-to-many relationships using rails. At that point, there was a part where I have to build a defined method for “create”. In that I misspelled “permit” by saying “premit”. That little can cause a whole lot of issues and sometimes the errors from “localhost:3000” won’t be able to help you because it will give you the wrong proper word. “Localhost:3000” is how to launch your rails using chrome to see the results of your website.

Another cause for miss-spelling or putting the right plurals is the cause to rush or panicking causing yourself not to think and just going straight to finishing your code. This had happed to me a lot during my challenge. During my challenge, I had to spend a little bit more on fixing migration issue causing me to louse time and started rushing my code. Their were other few things that I had messed up with as well, and some was from the view files called ActiveRecord Associations. These Associations can be run by using HTML to build buttons, creating a text field to create an interesting visuals. However, their was a part where I accidentally add plurals instead of making a singular for the variables. The reason why the variables should be singular instead of plural is because in my associations, the variables are connected to the ruby files called controllers(allows to create a request) and the variables has to be the same depending on where the views is connected to.

I always keep blaming on my computer constantly because after all the hard work that I did some of the links that I tried to fix is still not working and it’s not giving me an error. Below in this image I tried to click on a certain link that I’m very eager to make it work bit it never takes me to that certain page. It turns out that my define method called “create” in the joiner model is sending me to a wrong path.

Another example is that back in mod 1. I have to create a simple and an interesting app using just ruby. I created a simple library app where multiple users can be able to barrow many books from a library. Base on the mod 1 that we learned, in order for me to start this app, I had to create a new migration using the rake before migrating the file. However, the problem was that I’ve accidentally created two files that have plurals in them. One of them is in the migration file and the other file is in the model file. It’s never a good idea to have a same similar plurals because The program wont be able to know which one to connect to.

However, it’s not just misspelling, but also I keep missing the actual main codes. For example, During my mod 2 challenge I’ve got an error in my localhost saying that my associations has undefined method `appearances_path’. At first I didn’t understand what the heck the program was talking about. I tried looking at my associations again constantly, but my code is actually correct and it supposed to be connected properly. After the challenge, I was talking to my friend about the code that I was having issues with. It turns out that the cause for this code to fail was because I didn’t add “create” in my route file. The route is shown in the second image. To make it simple, route helps to redirect incoming requests to controllers and actions.


What or how to over come it:
-ALWAYS! ALWAYS! Double check your code before moving on.
-Check you variables

Installing package:
To anyone who is using using visual studio, please and try to install the packages because it will highlight to where you code has an error and it will be easier for you to find the blindspots.
-Error Lens
-Error Gutters
-status bar error

Using a byebug:
As for plurals or missing code, try to stick with using the “byebug” and type “params” in your terminal to check where your codes are connected to.
