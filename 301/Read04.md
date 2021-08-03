# React and Forms

## React Docs - Forms

1- What is a ‘Controlled Component’?

It is the component that takes its current value through props and notifies changes through callbacks like onChange .

2- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them?

We should update the state with their responses as soon as they enter them, because that input will be a cntrolled component by react and also controls what happens in that form on subsequent user input.

3- How do we target what the user is entering if we have an event handler on an input field?

By creating a function contains the passed in event parameter to get the target input element; from the target get the value and name of the input element.

## The Conditional (Ternary) Operator Explained

1- Why would we use a ternary operator?

Rewrite the following statement using a ternary statement:

```
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```

Insted of using a normal conditional we can use a  line of code to do the same Conditional by using Ternary Operator.

```
x===y ? 'Yes' : 'No';
```

## Things I want to know more about

learning more about React forms and how to use them.
