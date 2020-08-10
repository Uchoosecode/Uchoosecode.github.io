---
layout: post
title:      "State vs. Props"
date:       2020-08-10 02:07:02 +0000
permalink:  state_vs_props
---


In a React component, state are variables initalized and managed by the component. Props on the otherhand are still variables but passed to a child component from the parent component.  With that being said, state can be initialized by props.  An example of this would look like this, a parent component calls a child component <ChildComponent />. The parent is able to pass a prop like this <ChildComponent name=Ayako />.  We would access this prop in the ChildComponent constructor. That looks like this:
     constructor(props) 
		 {super(props)  
		 console.log(props.name) 
		 };
inside of the ChildComponent class. This enables you to reference the prop when we create any methods using this.props.  You can also use props to set the internal state based on the props in the constructor with the syntax this.state.userName = props.name.  Props also allows the child component access methods from the parent component.

Though you would want to refrain from changing the props in a child component.  Best practices is to manage the state in the parent component. This makes debugging simpler and avoind the children components from having the neeed to have their own state.

Which brings us to state, you never directly maniplate the state. In React anytime you want to change the state you use a method called setState( ). The setState( ) method ensures the component that it has been updated and then calls the render( ) method along with all other life cycle methods.  You should always put this. in front of setState( ). This will look like :
     constructor(props) {
     super(props);
     this.state = {
        name: "Ayako",
        age: 39}
        };
     changeName = ( ) => { this.setState({name: "Jamel", age: 40 }); }
		 
To wrap it up in simpliest terms, props are mainly for read only, you will get an error trying to change its value.  While the state is an object where you store property values, that value changes using the this.setState( ) method.
