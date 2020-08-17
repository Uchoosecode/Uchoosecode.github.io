---
layout: post
title:      "React Hooks are helpful!"
date:       2020-08-17 03:39:57 +0000
permalink:  react_hooks_are_helpful
---


A feature that's fairly new in React are the use of Hooks. Hooks allow you to extract stateful logic from a component, making it easier for that logic to be tested independently and reused.  Hooks allow you to reuse these logics without changing your component hieracrhy making it more simple to share Hooks to many components. In other words Hooks are functions that let you hook into React state and lifecycle features from functions components.  They don't work inside classes and they let you use React without classes.

Some rules to using Hooks, are you shouldn't use them in loops, conditions or nested functions. You should always use Hooks at Top-Level.  Don't call Hooks from regular Javascript functions. Use Hooks from React components and from custom Hooks. A good time to use Hooks is you write a function component and realize you have to add some state to it. Instead of changing it into a class component you can just add a Hook.


