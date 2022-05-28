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
function Car(props) {
return <h2>I am a { props.brand }!</h2>;
}
