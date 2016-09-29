The core of Phosphorus Five
===============

Here you can find the "core parts" of Phosphorus Five. There are five different projects in this folder;

* [lambda.exe](/core/lambda.exe/) which allows you to execute Hyperlisp in a console/terminal window
* [p5.ajax](/core/p5.ajax/) containing the Ajax library for ASP.NET
* [p5.core](/core/p5.core/) containing the Active Event design pattern implementation
* [p5.exp](/core/p5.exp/) containing the expression parser
* [p5.webapp](/core/p5.webapp/) being the main "application pool" for your web app/web site

When playing with P5, you should set the "p5.webapp" project as your startup project. 

The "p5.webapp" project, is really just a simple website, allowing for you to create plugins for, which you can use in your own
code. By default, it comes with "System42" pre-installed, which is a simple GUI front-end/back-end for your system, containing
pieces like a fully fledged CMS or publishing system, the ability to browse files and folders on your system, managing users, etc.
But System42 can easily be entirely removed by deleting the "system42" folder, and changing your web.config to point to another 
"startup file".

In fact, when you create web apps and/or websites, then the only projects you'd normally need to include a reference to, are these;

* p5.ajax, if you wish to have Ajax functionality in your project
* p5.core, if you wish to consume Active Events in your project
* p5.exp, if you wish to use expressions in your project

In addition, you could also choose to use the "p5.webapp", either as a starting ground for your own ASP.NET website project, or hosting
your entire application, adding up all your own functionality as plugins. However, all projects are actually optional, and you can use
any single part of Phosphorus Five, without needing to use any other parts.


