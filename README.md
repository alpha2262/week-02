# Quiz #2

## Instructions

1. Fork this repo
2. Clone your fork
3. Fill in your answers by writing in the appropriate area, or placing an 'x' in
the square brackets (for multiple-choice questions).
4. Add/Commit/Push your changes to Github.
5. Open a pull request.

## JavaScript

### Question #1

**What of the following are JavaScript Data Types?**

Select all that apply:
```
[X] String
[X] Boolean
[X] Undefined
[] NaN
[X] Number
[] Array
[X] Null
```

## Question #2

Explain what is a REPL, and why is it important for us as developers and help with debugging?

```text
It's the ability to "see" the code process bit by bit to discover errors and/or why the data is not updating as you think it should.

```
### Question #3

**Given the Following Array**

var foods = [ ["apple","banana","strawberry"], ["pizza","fries","hamburger"] ];

Create a For Loop that outputs the following string for each piece of fruit in the console. "I want to eat a [fruit]"

```js

for i in foods (){
  i <6, i++, "I want to eat a " + i + "."
}


```
### Question #4

**Given the Following Array**

var foods = [ ["apple","banana","strawberry"], ["pizza","fries","hamburger"] ];

How would I go about accessing the string "pizza" in the above array?

```js
// write code here

console.log[1][0]

```

## Scope/Context/Closures

### Question #5

Describe the rules of scope in JavaScript.

Your Answer:
```
Scope is what can be "seen" by JavaScript code and executed or otherwise impact, the triangle of view. A child function can impact a parent while the child function's value could not impact a function outside of the parent.

```

### Question #6

Define an object and store it in a variable `pizza`. The object should have 2
properties: a temperature (set to 70), and a method called `bake`. When called,
this method should set the pizza's temperature to be 300. Note: you may not use
the variable pizza inside your method.

Your Answer:
```js
An object is a one or more collection of values with key value pairs e.g. fruit [apple, banana]

var pizza = [ ["temperature"]; [70], ]

function bake(){
  for temperature <300 {
    temperature.push 1++
  }
}

**note for self: look up/try this, not sure it will work as written***

// write code here
```

### Question #7

Define a global variable instructor and set it equal to your Squad Instructor's Name. Then, define the same as a local variable instead.

Your Answer:
```js
// write code here

var instructor = "Jessie"

function x (){
  var instructor = "Jessie"
}


```

## Objects and Functions

### Question #8

What are the differences between calling and referencing a function? Please provide examples of each.

```text
Calling a function provides a value based on the function executing.

Referencing a function, I'm not sure based on looking online but it seems like it might a function that could be called but isn't.


```
### Question #9

Using the object literal notation, Define an object called student and give it the properties (your attributes) of name, age, and a method sayHello, that outputs "Hi, my name is [your_name]".

Your Answer:
```js
// write code here

var student = {
  firstName: "Michael",
  lastName: "Holzheimer",
  age:29,

  function sayHello(){
    "Hi, my name is " + firstName + " " + lastName "."
  } 
}

```

## Callbacks

### Question #10

**What is the difference between synchronous and asynchronous program execution?**

Select all that apply:
```
[] Synchronous code runs at an even pace, asynchronous code runs with uneven pacing.
[] Synchronous code runs all at the same time, asynchronous code runs completely randomly
[X] Synchronous code runs in order (as appears in the source), asynchronous code may run at a later time.
```
