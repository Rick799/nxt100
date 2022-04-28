# Javascript Variables

- **_var_**: The most commonly used variable in JavaScript is var. It can be redeclared and its value can be reassigned, but only inside the context of a function. <br>
- **_const_**: const variables in JavaScript cannot be used before they appear in the code. They can neither be reassigned values, that is, their value remains fixed throughout the execution of the code, nor can they be redeclared.<br>
- **_let_**: The let variable, like const, cannot be redeclared. But they can be reassigned a value.<br>

# Data Types

- **String** represents textual data
- **Number** an integer or a floating-point number
- **BigInt** an integer with arbitrary precision
- **Boolean** Any of two values: true or false
- **Undefined** a data type whose variable is not initialized
- **Null** denotes a null value
- **Symbol** data type whose instances are unique and immutable
- **Object** key-value pairs of collection of data
  <br><br>

# JavaScript Operators

**Fundamental Operators**: These operators are used to perform basic operations like addition, multiplication, etc. in JavaScript.
<br><br>

**Bitwise Operators**: All the operations dealing with the bits of the numbers can be performed by the bitwise operators in JavaScript.

- `&` : AND Sets each bit to 1 if both bits are 1
- `|` : OR Sets each bit to 1 if one of two bits is 1 -`^` XOR Sets each bit to 1 if only one of two bits is 1
- `~` : NOT Inverts all the bits
- `^` : The bitwise XOR operator () returns a 1 in each bit position where the corresponding bits of both operands are 1s but not both.
- `<<` : The _left shift operator_ shifts the first operand to the left by the provided number of bits. Extra bits that have been relocated to the left are discarded. From the right, zero bits are shifted in.
- `>>` : The _right shift operator_ (>>) moves the first operand to the right by the provided number of bits. Extra bits that have been relocated to the right are discarded. The leftmost bit's copies are shifted in from the left.

  **Comparison Operators**:

- `==` Equal to: true if the operands are equal 5==5; //true
- `!=` Not equal to: true if the operands are not equal 5!=5; //false
- `===` Strict equal to: true if the operands are equal and of the same type 5==='5'; //false
- `!==` Strict not equal to: true if the operands are equal but of different type or not equal at all - 5!=='5'; //true

- `>` Greater than: true if the left operand is greater than the right operand 3>2; //true
- `> =` Greater than or equal to: true if the left operand is greater than or equal to the right operand 3>=3; //true
- `<` Less than: true if the left operand is less than the right operand 3<2; //false
- `<=` Less than or equal to: true if the left operand is less than or equal to the right operand 2<=2; //true
  <br><br>

# If-Else Statements

**\*if** (check condition) {<br>
// block of code to be executed if the given condition is satisfied<br>
} **else** {<br>
// block of code to be executed if the given condition is not satisfied<br>
}\*
<br><br>

# Loops

**_the for loop_** : <br>
**for** (_initialization of the loop variable ; condition checking for the loop ; updation after the loop_)<br> { <br>
// code to be executed in loop <br>
}

**_the while loop_**:<br> Establishes the conditions under which a loop will run.

// Initialization of the loop variable is done before the while loop begins<br>
**while**(_condition checking for the loop_)<br>{<br>
// _1. code to be executed in loop<br>
// 2. updation of the loop variable_<br>
}

**_the do-while loop_**: <br>Similar to the while loop, but it runs at least once and checks at the end to see whether the condition is met to run again

// Initialization of the loop variable is done before the do-while loop begins<br>
**do**<br>{<br>
// _1. code to be executed in loop<br>
// 2. updation of the loop variable_<br>
}<br> **while**(_condition checking for the loop_);

There are two statements that are important in the context of loops:

- **_continue statement_**: Skip parts of the loop if certain conditions are met.
- **_break statement_**: Used to stop and exit the cycle when specific conditions are met.
  <br><br>

# Arrays

They are a method of categorising variables and attributes. Arrays can be defined as a collection of objects of the same type.

- **_pop( )_**: This method is used for removing the last element of an array.
- **_push( )_**: This method is used for adding a new element at the very end of an array.
- **_concat( )_**: This method is used for joining various arrays into a single array.
- **_reverse( )_**: This method is used for reversing the order of the elements in an array.
- **_shift( )_**: This method is used for removing the first element of an array.
- **_slice( )_**: This method is used for pulling a copy of a part of an array into a new array.
- **_splice( )_**: This method is used for adding elements in a particular way and position.
- **_toString( )_**: This method is used for converting the array elements into strings.
- **_unshift( )_**: This method is used for adding new elements at the beginning of the array.
- **_valueOf( )_**: This method is used for returning the primitive value of the given object.
- **_indexOf( )_**: This method is used for returning the first index at which a given element is found in an array.
- **_lastIndexOf( )_**: This method is used for returning the final index at which a given element appears in an array.
- **_join( )_**: This method is used for combining elements of an array into one single string and then returning it.
- **_sort( )_**: This method is used for sorting the array elements based on some condition.
  <br><br>

# Functions

_function nameOfTheFunction ( parameterOne, parameterTwo, parameterThree, parameterFour,....,parameterN)<br> { <br>
// Job or Task of the function<br>
}_

**Functions For Throwing Data As Output**: The output of data is a common application for functions. You have the following options for outputting data:

- **_prompt( )_**: This function is used for creating a dialogue box for taking input from the user.
- **_alert( )_**: This function is used for outputting information in an alert box in the browser window
- **_console.log( )_**: This function is used for writing data to the browser's console and is used for the purpose of debugging code by developers.
- **_document.write( )_**: This function is used for writing straight to our HTML document
- **_confirm( )_**: This function is used for opening up a yes or no dialogue box and for returning a boolean value depending upon the user's click.

**Global Functions**: Every browser that can run JavaScript has a set of global functions built-in. Some of them are as follows:

- **_parseFloat( )_**: This function is used for parsing the argument passed to it and returning a floating-point number.
- **_parseInt( )_**: This function is used for parsing the argument passed to it and returning an integral number.
- **_encodeURI( )_**: This function is used for encoding a URI into a UTF-8 encoding scheme.
- **_decodeURI( )_**: This function is used for decoding a Uniform Resource Identifier (URI) made by encodeURI() function or similar functions.
- **_encodeURIComponent( )_**: This function is used for the same purpose as encodeURI() only for URI components.
- **_decodeURIComponent( )_**: This function is used for decoding a URI component.
- **_isNaN( )_**: This function is used for determining if a given value is Not a Number or not.
- **_Number( )_**: This function is used for returning a number converted from what is passed as an argument to it.
- **_eval( )_**: This function is used for evaluating JavaScript programs presented as strings.
- **_isFinite( )_**: This function is used for determining if a passed value is finite or not.
  <br> <br>

# Objects

In JavaScript, an **_object_** is a standalone entity, with properties and type. <br>
A property of an object can be explained as a variable that is attached to the object. The properties of an object define the characteristics of the object.

_const myCar = {<br>
make: 'Ford',<br>
model: 'Mustang',<br>
year: 1969<br>
};_ <br> <br>

# Scope<br>

The accessibility or visibility of variables in JavaScript is referred to as **_scope_**. That is, which sections of the program can access a given variable and where the variable can be seen. There are usually three types of scopes:

- **_Global Scope_**: The global scope includes any variable that is not contained within a function or block (a pair of curly braces). Global scope variables can be accessed from anywhere in the program.

- **_Local or Function Scope_**: Variables declared inside a function are local variables. They can only be accessed from within that function; they are not accessible from outside code.

- **_Block Scope_**: Unlike var variables, let and const variables can be scoped to the nearest pair of curly brackets in ES6. They can't be reached from outside that pair of curly braces, which means they can't be accessed from the outside.<br><br>

# JavaScript Closures

A **_closure_** is a function that has been bundled together (enclosed) with references to its surroundings (the lexical environment). In other words, a closure allows an inner function to access the scope of an outside function. Closures are formed every time a function is created in JavaScript, during function creation time.
