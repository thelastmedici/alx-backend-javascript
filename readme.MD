# Curriculum

## Short Specializations
Average: 0.0%
0x00. ES6 Basics
JavaScript
ES6
Weight: 1
Project will start Aug 5, 2024 6:00 AM, must end by Aug 6, 2024 6:00 AM
Checker will be released at Aug 5, 2024 12:00 PM
An auto review will be launched at the deadline

## Concepts
For this project, we expect you to look at these concepts:
- JavaScript programming
- Software Linter

## Resources
Read or watch:
- ECMAScript 6 - ECMAScript 2015
- Statements and declarations
- Arrow functions
- Default parameters
- Rest parameter
- Javascript ES6 — Iterables and Iterators

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
- What ES6 is
- New features introduced in ES6
- The difference between a constant and a variable
- Block-scoped variables
- Arrow functions and function parameters default to them
- Rest and spread function parameters
- String templating in ES6
- Object creation and their properties in ES6
- Iterators and for-of loops

## Requirements
General
- All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the js extension
- Your code will be tested using the Jest Testing Framework
- Your code will be analyzed using the linter ESLint along with specific rules that we’ll provide
- All of your functions must be exported

## Setup
Install NodeJS 12.11.x
(in your home directory):
```
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
$ nodejs -v
v12.11.1
$ npm -v
6.11.3
```
Install Jest, Babel, and ESLint
in your project directory, install Jest, Babel and ESList by using the supplied package.json and run npm install.

## Configuration files
Add the files below to your project directory
- package.json
- babel.config.js
- .eslintrc.js

Finally…
Don’t forget to run npm install from the terminal of your project folder to install all necessary project dependencies.

## Tasks
### 0. Const or let?
mandatory
Modify
```javascript
function taskFirst() {
    var task = 'I prefer const when I can.';
    return task;
}

function getLast() {
    return ' is okay';
}

function taskNext() {
    var combination = 'But sometimes let';
    combination += getLast();

    return combination;
}
```
to instantiate variables using const in `taskFirst` and using let in `taskNext`.

### 1. Block Scope
mandatory
Given what you’ve read about var and hoisting, modify the variables inside the function `taskBlock` so that the variables aren’t overwritten inside the conditional block.

### 2. Arrow functions
mandatory
Rewrite the following standard function to use ES6’s arrow syntax of the function `add`.

### 3. Parameter defaults
mandatory
Condense the internals of the following function to 1 line - without changing the name of each function/variable.

### 4. Rest parameter syntax for functions
mandatory
Modify the following function to return the number of arguments passed to it using the rest parameter syntax.

### 5. The wonders of spread syntax
mandatory
Using spread syntax, concatenate 2 arrays and each character of a string by modifying the function below.

### 6. Take advantage of template literals
mandatory
Rewrite the return statement to use a template literal so you can substitute the variables you’ve defined.

### 7. Object property value shorthand syntax
mandatory
Modify the following function’s budget object to simply use the keyname instead.

### 8. No need to create empty objects before adding in properties
mandatory
Rewrite the `getBudgetForCurrentYear` function to use ES6 computed property names on the budget object.

### 9. ES6 method properties
mandatory
Rewrite `getFullBudgetObject` to use ES6 method properties in the `fullBudget` object.

### 10. For...of Loops
mandatory
Rewrite the function `appendToEachArrayValue` to use ES6’s for...of operator. And don’t forget that var is not ES6-friendly.

### 11. Iterator
mandatory
Write a function named `createEmployeesObject` that will receive two arguments: `departmentName` (String) and `employees` (Array of Strings).

### 12. Let's create a report object
mandatory
Write a function named `createReportObject` whose parameter, `employeesList`, is the return value of the previous function `createEmployeesObject`.
