---
layout: post
title:      "Why I am grateful for ES6"
date:       2020-08-31 03:49:47 +0000
permalink:  why_i_am_grateful_for_es6
---


As a coder using the Javascript language, ES6 is the preferred version use to write programs.  ES6 is also known as ECMAScript 6 or Javascript 6.  This version was introduced in 2015.  As coder we are always thinking are ways to write less code to handle the same tasks and to make it easier to understand or debug someone else's code.  Some of the features added when ES 6 was introduced was Javascript *let*, Javascript *const*, *Arrow Functions*, *Classes* and *Default Parameters Values*.  Before ES6 there was only 2 types of Scope, A **Global Scope** and a **Function Scope**. ES6 introduced the **Block Scope**.

The *let* and *const* keywords lets you use **Block Scope** variables and constants in Javascript.  This means variables created with those keywords inside of a block(**{}**) cannot be accessed outside of the block.  This was not the case before ES6.  This feature make redeclaring variables easier.  I actually discussed these keywords in a previous blog so I'm gonna move on.

*Arrow Functions* allows a shorter syntax for writing function declariations. An eample of this is ***let a = (a, b ) => a + b;***.  When using arrow functions you don't need the *function* keyword, if the function is a single statement, you dont need the keyword *return* or even the curly braces. Though using the curly braces is still a best practice regardless. You can still pass parameters inside the parenthesis. They don't have their own *this*, so really good for defining object methods. They don't get hoisted, so they must be defined before they're declared.

*Classes* are functions that now use the keyword *class* instead of *function* to initate it.  The properties for the *class* is assigned using the *constructor( )* method.  Whenever the class object is initalized the constructor method automatically gets called. Classes allows you to use getters and setters by using the keywords *get* and *set*. Classes allows you to create class inheritance using the keyword *extends*.  This allows a class to inherit all the methods from another class.

This are just some of the new features that ES6 has made available. It is the most popular version that has been introduced to the ECMAScript family. There are many other features I suggest you look up that canbe extremely useful in all of your future productions.
