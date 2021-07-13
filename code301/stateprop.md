# State and Props

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
-- render happens first

2. What is the very first thing to happen in the lifecycle of React?
-- The constructor is called

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
-- constructor, render, componentDidMount, React Updates, ComponentWillUnmount

4. What does componentDidMount do?
-- It is used to load anything over the network or to initialize the DOM.

## React State vs. Props

1. What types of things can you pass in the props?
-- The same things you would pass to a function as arguments

2. What is the big difference between props and state?
-- State exists inside a component while props are passed into a component. State is updated in a component while props are updated outside of a component.

3. When do we re-render our application?
-- When the user has done something and it needs to update

4. What are some examples of things that we could store in state?
-- A form, anything that the user is interacting with

## Things I want to know more about

1. What exactly is state? I keep seeing it but I don't understand it yet... it seems to be like a function- limited scope and handles one aspect of the app, but I'm not sure.