# State and Props

-------

1- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

- The render

2- What is the very first thing to happen in the lifecycle of React?

- Mounting phase by the constructor or something else.

3- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- constructor (at the first of mounting phase)
- render (also during mounting phase)
- componentDidMount (after finishing mounting phase)
- componentWillUnmount(finally if you removed the component, unmounting phase.)
- React Updates

4- What does componentDidMount do?

- It is a method that will be invoked after finishing creating the component and mounting phase, you can call things you would see after the rendering process.

5- What types of things can you pass in the props?

- It is like arguments in the functions, it can pass numbers, texts, or anything else you want.

6- What is the big difference between props and state?

- First difference: props pass into the component and it handled outside the component. but the state is handled inside the component itself.
- Second difference: state used when you need to re-render your application after some data changing from the user. but props used when you need to display something in your application and you can't update its value or re-render again without hard coding.

7- When do we re-render our application?

- When the data of the component changes, it will be re-rendered directly. we can make our data changes by user action using states.

8- What are some examples of things that we could store in state?

- You can use state with forms to store the data from the user; like texts, numbers, checkboxes(true or false), and so on.
- Also you can use state with everything you want to change dynamically by user request; like a counter that changes every time for the same component.

## Things I want to know more about

- I would to practice with state and props. Also, using reseved methods in classes.
