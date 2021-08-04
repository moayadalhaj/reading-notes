# Putting it all together

------

## Thinking in React

1- How would you break a mock into a component hierarchy?

- You have to select UI content and convert them to components, one component for each element, and sort them from parent to child.

2- What is the single responsibility principle and how does it apply to components?

- This principle means that every component should have one function to do, if the component has more than one function then make subcomponents as children to it, every child will do one function.

3- What does it mean to build a ‘static’ version of your application?

- That is means you will not be able to change your data. in another meaning; you will not use state into your components.

4- Once you have a static application, what do you need to add?

- You have to make it dynamic, by using states into each component that needs to change its data.

5- What are the three questions you can ask to determine if something is state?

- If it is able to move from its component(parent to child)? if not, maybe it is not state.
- If its value still fixed over time? if yes, it is not state.
- If it depends on other states and props? if yes, it is not state.

6- How can you identify where state needs to live?

- Based on where it will be used and rendered? sometimes you have to pass this state from its component to another to render it there.

## Things I want to know more about

- Knowing more react and bootsrap by also all things about classes.
