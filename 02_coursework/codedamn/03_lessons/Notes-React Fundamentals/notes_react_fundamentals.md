## INTRODUCTION

**_React_** is a library for building user interfaces. React is not a framework – it's not even exclusive to the web. It's used with other libraries to render to certain environments.
To build for the web, developers use React in tandem with ReactDOM. React and ReactDOM are often discussed in the same spaces as — and utilized to solve the same problems as — other true web development frameworks.
React's primary goal is to minimize the bugs that occur when developers are building UIs. It does this through the use of components — self-contained, logical pieces of code that describe a portion of the user interface. <br><br>

## COMPONENTS<br><br>

**_Components_** are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML.

Components come in two types:  
_**<li>Class** components</li>_ <br>
_**<li>Function** components</li>_<br>

**_Class Component_**<br><br>
A Class component must include the extends React.Component statement. This statement creates an inheritance to React.Component, and gives your component access to React.Component's functions.

<code>
    class Car extends React.Component { <br>
    render() { <br>
    return <h2>Hi, I am a Car!</h2>; <br>
    } <br>
    }
</code>

The component also requires a **render()** method, this method returns HTML. <br><br>

**_Function Component_**

A Function component also returns HTML, and behaves much the same way as a Class component, but Function components can be written using much less code, are easier to understand.

<code>
    function Car() { <br>
    return <h2>Hi, I am a Car!</h2>; 
    }
</code> <br><br>

## Rendering a Component

<code>
    
    const root = ReactDOM.createRoot(document.getElementById('root')); 
    root.render(<Car />);
</code>

## PROPS

**_Props_** are arguments passed into React components. <br>
**_Props_** are passed to components via HTML attributes.

The component receives the argument as a props object: <br>
<code>
function Car(props) {
return <h2>I am a { props.brand }!</h2>;
}
</code>

## CONDITIONAL RENDERING

In **_React_**, we can render multiple components on the basis of certain conditions or on the basis of the state of the application. A component in ReactJS thus decides which elements to return depending on one or more conditions. Conditional rendering in React is the same as the conditions in JavaScript.

<li>If</li>
It is the easiest way of conditional rendering in ReactJS. It returns the element to be rendered if the condition is true.

<li>Logical && operator</li>
It returns the element right after && if the condition is true. It ignores and skips if the condition is false.

<li>Ternary operator</li>
It is used to act as a concise if-else statement, for cases where two blocks alternate given a certain condition. Here, the true statement will be rendered, if the condition is true, and if it is false, the false statement will be rendered. <br><br>

# HOOKS

**_Hooks_** allow function components to have access to state and other React features. Hooks allow us to "hook" into React features such as state and lifecycle methods.

Hook Rules
There are 3 rules for hooks:

<li>Hooks can only be called inside React function components.</li>
<li>Hooks can only be called at the top level of a component.</li>
<li>Hooks cannot be conditional</li> <br><br>

# STATE

In a component, state is data we import — typically to show the user — that is subject to change. It could change because the database we’re getting from may be updated, the user modified it etc. <br>

## Changing the state Object

To change a value in the state object, use the **_this.setState()_** method.

When a value in the state object changes, the component will re-render, meaning that the output will change according to the new value(s). <br><br>

# useState Hook

The React useState Hook allows us to track state in a function component.

<code>import { useState } from "react";</code>

useState accepts an initial state and returns two values:

<li>The current state.</li>
<li>A function that updates the state.</li>

<code>
    import { useState } from "react";
    
    function FavoriteColor() {
      const [color, setColor] = useState("");
    }
</code>

# useEffect Hook

The **_useEffect_** Hook allows you to perform side effects in components.

Some examples of side effects are: **_fetching data, directly updating the DOM, and timers_**.

useEffect accepts two arguments. The second argument is optional.

<code>useEffect(function, dependency)</code>
