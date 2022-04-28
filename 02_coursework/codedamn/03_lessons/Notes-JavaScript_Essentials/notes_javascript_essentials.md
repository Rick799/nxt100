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
