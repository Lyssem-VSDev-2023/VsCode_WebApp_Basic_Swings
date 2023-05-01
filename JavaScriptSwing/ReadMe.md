<style>
    r { color: Red }
    o { color: Orange }
    g { color: Green }
    bl { color: blue; text-decoration:underline }
</style>

<br><HR>

# **Intro to Javascript**

<br>
<br>

# Table of Content

1. [Variables Declaration](#1-variables-declaration)
1. [Numbers](#2-numbers)
1. [Strings](#2-strings)

<br>
<br>

<!---------------------Variables Declaration----------------------------->

# 1. Variables Declaration

## <bl>var and let</bl>

```javascript
var aVariable; // Visible outside Code Block {}
aVariable = 321;

let myVariable; // only accessible within Code Block {}
myVariable = 123;
let myVariable2 = 123; //let cannot be reassigne
```

## <bl>const</bl>

```javascript
const MY_VARIABLE = 123; // Fixed value at declaration
const PI = 3;
PI = 4; // not allowed

const obj = { a: 3 };
obj = { b: 5 } // not allowed

const obj2 = { a: 3 };
obj.a = 5;  // allowed
```

## <bl>Data Types</bl>

- string, 
- number, 
- bigint, 
- boolean, 
- undefined, 
- and symbol

<br>

<!---------------------Numbers----------------------------->

# 2. Numbers

Those are the allowed operations:

|Symbol|	Description|
|:-:|-|
|+	|Addition: Calculates the sum of two numbers.|
|-	|Subtraction: Calculates the difference of two numbers.|
|*	|Multiplication: Calculates the product of two numbers.	|
|/	|Division: Calculates the quotient of two numbers.	1|
|%	|Remainder: Calculates the remainder from the division of two numbers.|

<!---------------------Strings----------------------------->

# 2. Strings

- 'This is a string'
- "This is also a string"
- let myString = 'This is a string value stored in a variable';

```javascript
let myString1 = "Hello";
let myString2 = "World";

myString1 + myString2 + "!"; //HelloWorld!
myString1 + " " + myString2 + "!"; //Hello World!
myString1 + ", " + myString2 + "!"; //Hello, World!
```