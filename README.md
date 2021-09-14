# AJ's Notes
---
##### [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Summary 

This repository contains all of the notes taken by [AJ](https://github.com/smartnvm) for the [Lighthouse Labs](https://lighthouselabs.ca) Web Development Bootcamp.

## Table of Contents

* [Week 1](/wk1)
  * [Day 1](/wk1/d1/What_Should_I_Do_for_Lunch_Tips.md)
  

## Day 1
  ### process.argv

  we can pass paramters to script seperated by space

  ```javascript
  node sum.js param1 param2 ...
  ```
  
  
  ### console.log() with Emoji 
  we can print emoji to the console
  1) copy paste the emoji 
  2) use codepoint 
  
 ```javascript
  const happyFace = String.fromCodePoint(128516);
  const sickFace = String.fromCodePoint(129314);
  console.log(happyFace + ` Assertion Passed: ${actual} === ${expected}`) :
  console.log(sickFace + ` Assertion Failed! ${actual} !== ${expected}`);
```



---

## Day 2

he way a function is decalared has to do with "hoisting"

with function declaration we can call the function prior to the declaration
with expression function has to be done prior to funciton call 

arrow function are function expression 



```javascript
//function declaration 
function getArgument () {

}


//function expression 
const getArgument  = function(){

}

```

t

  