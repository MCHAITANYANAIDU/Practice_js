# Practice_js
core programming 



--------------------------------
variables->
variables are like containers which are used to store the data and manipulate the data 
   var mybox; ----variable declaration
 declared in 4 ways
 1.var
 2.let
 3.const
 4.let and const are block scoped and var is function scoped
 var mybox = 10;----variable initialization

 let is a block scoped and is prefearable for variable declaration
 const is also block scoped but its value cannot be re assigned once it assigned

 global variable--> outside any function have a global scope and can be accessed and modified from any part of the script

 local variable-->variables declared within a function have local scope and can be only accessible within in that function
 -------------------------------------------------------------------------------
HOISTING:
-->variables declarations are hoisted to the top of thier scope during the compilation phase,but thier assignments remains where they are...
----------------------------------------------------------------------------------
DATA TYPES:
-->Primitive datatypes
-->non-primitive datatypes
-->Special datatype
PRIMITIVE DATA:
*fundamental building blocks used to represent single values
*directly stored in memory
*Immutable-cannot be changed after they are created
-->numbers,boolean,strings,undefined,null,symbol
*null:represents the intentional absence of any object value
*undefined:represents an uninitialized variable or an expression that has not been evaluated yet
*symbol:represents a unique and immutable primitive value


NON-PRIMITIVE DATATYPES:
*also know as reference type
*more complex data structures that can hold multiple values and have methods and properties
*Mutable:values can be changed after they are created
*stored and accessible by refernce rather they by value
*objects:
-->collection of key-value pairs
-->keys are strings and values can be any datatype
*arrays:
-->an ordered collection of elements accessed by index,starting from zero

SPECIAL DATATYPE:
*function: a block of code that can be executed multiple times from different parts of the script
*function is a first class citizen in javascript
*can be passed as an argument to another function
*can be returned from a function
*can be stored in a variable
*can be stored in an array
*can be stored in an object

---------------------------------------------------------------------------------------------------------------
OPERATORS:
-->Arithmetic operators
-->Comparison operators
-->Logical operators
-->Assignment operators
-->Bitwise operators
-->String operators


ARITHEMTIC OPERATORS:
-->addition: a + b
-->subtraction: a - b
-->multiplication: a * b
-->division: a / b
-->modulus: a % b
-->exponentiation: a ** b
-->increment: a++ or ++a
-->decrement: a-- or --a
-->unary plus: +a


ASSIGNMENT OPERATOR:
-->assignment: a = b
-->addition assignment: a += b
-->subtraction assignment: a -= b
-->multiplication assignment: a *= b
-->division assignment: a /= b
-->modulus assignment: a %= b
-->exponentiation assignment: a **= b
-->bitwise AND assignment: a &= b
-->bitwise OR assignment: a |= b
-->bitwise XOR assignment: a ^= b
-->bitwise NOT assignment: a ^= b
---------------------------------------------------------------------------------------------------------------

conditional statements:
-->if statement: used to execute a block of code if a condition is true
-->if-else statement: used to execute a block of code if a condition is true, otherwise
execute another block of code
-->switch statement: used to execute a block of code based on the value of a variable
-->try-catch statement: used to handle exceptions and errors in the code
-->nested if else


---------------------------------------------------------------------------------------------------------------
control structures:
-->loops: used to execute a block of code repeatedly
-->conditional statements: used to execute a block of code based on a condition
-->break statement: used to exit a loop or switch statement
-->continue statement: used to skip the current iteration of a loop
-->pass statement: used to do nothing and continue with the next line of code
-->return statement: used to exit a function and return a value
-->goto statement: used to jump to a specific label in the code
-->yield statement: used to pause the execution of a function and resume it later


loops:
-->for loop: used to execute a block of code repeatedly for a specified number of times
syntax:
for (initialization; condition; increment/decrement)
{
  // code to be executed
  }


<!-- n=+prompt("enter the value:")
for(i=0;i<=10;i++)
    {
        // console.log(n*i);
        console.log(n+"*"+i+"="+n*i)
        } -->



-->while loop: used to execute a block of code repeatedly while a condition is true
syntax:
while (condition)
{
  // code to be executed
  }


-->do-while loop: used to execute a block of code repeatedly while a condition is true
syntax:
do
{
  // code to be executed
  }
  while (condition);
  -->foreach loop: used to iterate over a collection of items
  syntax:
  foreach (variable in collection)








