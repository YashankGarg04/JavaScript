# JavaScript
This repository consist of my learning phase project for the language Java script
>**Note:** The README file here consist of some quick code methods which could help as a Cheat Sheet in Future
## Some Conceptual Codes
### String Concept Codes
```
var Name = "Yashank";
console.log(Name.length); // Will Return Length of the string Name 
console.log(Name.slice(0,1)); //Will return "Y" where in slice parameters initial is included but 1 is not included
Name.toUpperCase();
Name.toLowerCase();
```
## Important Notes
### Variables
* Variable `var` can be defined in a global Scope or Block scope it will work still work everywhere 
* Variables can be redeclared which means you can change the type of the variable , For Example
```
var a = 7;
var a = "Ms. Dhoni";
```
* Variables can be ReAssigned, also if we reassign a variable Inside the block its value gets changed globally
* Variables can be Hoisted 
> **Note:** Hoisted is a method used in a code where even if we declare a variable between a code we can use it anywhere in the code We can only use hoisting with `var`
### Let
* `let` if defined in block scope then cannot be used outside the Block
* Let cannot be reDeclared
* Let can be reAssigned, though if assigned within a block then that wouldnot change the value outside the Block, for example
```
let a = 10;
{
    let a =5;
    // Value here is 5
}
//Value here is 10
```
* Let cannot be Hoisted
### Const
Const is a one time declared value 
* `const` if defined in block scope then cannot be used outside the block
* It can neither be reDeclared nor reAssigned nor Hoisted

## Important Operators
* `==` : Equal to
* `===` : Equal to and Equal Type
* `!==` : Not Equal to not Equal Type
* `?` : ternary Operator, e.g,, `a>b?a:b` for finding the greator value
* `&&` : logical AND
* `||` : logical OR
* `!` : not

## Data Types
```
// Numbers:
let length = 16;
let weight = 7.5;

// Strings:
let color = "Yellow";
let lastName = "Johnson";

// Booleans
let x = true;
let y = false;

// Object:
const person = {firstName:"John", lastName:"Doe"};

// Array object:
const cars = ["Saab", "Volvo", "BMW"];

// Date object:
const date = new Date("2022-03-25");
```
## Functions