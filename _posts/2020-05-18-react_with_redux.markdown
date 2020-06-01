---
layout: post
title:      "React with Redux"
date:       2020-05-18 00:55:27 -0400
permalink:  react_with_redux
---


For this project I used React with Redux.  What I enjoy the most about React is that it's front-end based. It uses Components to separate the responsibilties of different visual aspects.  Components let you split the UI into reusable pieces. Also the introduction of JSX very useful.  JSX is the combination of HTML and Javascript, which makes everything more understandable,declaritive and flexible while you're in the development phase.  When using components, its best to organize by thinking of your components as either a Presentational Component or a Containers Component. Presentational Components basically deal with what is beening seen.  Containers Components deals with managing the information.  Components use state and props to handle data.  State is where the data comes from.  Props is used for sending data between Components.  The main difference between state and props is that props are immutable, they're basically for rendering purposes while the state is meant to handle changes in the components. 

Another introduction with using React is the LifeCycle Methods.  There is 3 types of life cycle methods. Mounting lifecycle methods which is called before it's created. Updating lifecycle methods which is called after is been created. Dismounting lifecycle method when it's about to be deleted or stopped.  Some examples of a these methods are render(), constructor, componentDidUpdate() and componentWillUnmout(). On my project I used mostly mounting lifecycle methods. I used componentDidMount for my fetch requests.

My favorite addition for me while doing this project was being able to use yarn start which lets you seeing your project all coming together live while you're coding, what is known as the virtual DOM. This was extremely helpful with using inline declarations and CSS.  It also made debugging easier and made developing UI more engaging. 

The addition of Redux takes our data and puts it in one place. Redux is basically a Javascript library used to manage application state.  Combined with React, its used for building UI. Components can get data from a Redux store.  Thhe simplest way to explain this is the Store holds data, that data is defined for UI, the user triggers an action, that Action is then sent to a reducer and the Reducer updates the store.  This is the unidirectional data flow of React Redux. We also use a middleware called Redux Thunk.  Thunk is used to handle the asynchronous request to the application. It's does this my using a method called dispatch which  allows us to call a function within the action creators.  Usually the action creators returns a typcial Javascript object.  The returned function recieves the store's dispatch function and is able to add multiple action that will load state and then another function to updatethe store with that returned data.  

I decided to test myself while doing this project and used no outside help other than the cirriculum videos and information I researched for more understanding, being this was the final project of this training.  Armed with everything I've learned I am ready for the next step in this journey now ...to be continued!
