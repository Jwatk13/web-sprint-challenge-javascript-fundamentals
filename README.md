# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks. 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results. 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 
Answer: The `.map` method creates a new array using the results on the called array elements and it's own function. 
The `.reduce` method executes a user-supplied callback function on each element of the array, in order, passing in the return value from the calculation on the preceding element. The final result of running th ereducer across all elements of the array is a single value.
The `.filter` method creates a new array of all the elements it filtered from the array it was called on.
Use Cases: `.map` - This method is best used when you want a function to iterate over all the values of an array in order and return the new values of the function result on the old values. For example, if you want to multiply every number in array by five and return the result. 
`.reduce` - This method is best used to reduce many values to one value, for example, returning the sum of many values.
`.filter` - This would be good to use when you are looking for a specific value, for example, returning only numbers greater than 10 from an array.

2. Explain the difference between a callback and a higher order function.
Answer: A higher-order function is one that accepts functions as parameters and/or returns a function. 
A callback function is, for example, one of the functions set as a parameter in the higher-order function.

3. Explain what a closure is.
Answer: A closure can be used to make global variables private. When using closure, the function within the scope of another function, is able reach outside of its scope to have access to 'global' variables.

4. Describe the four principles of the 'this' keyword.
Answer: 1.) Window Binding - is what happens when there is no context for the 'this' keyword that we used. Since it has no direction, it returns the window to us, or undefined.
2.) Implicit Binding - Here the 'this' keyword just responds to whatever is to the left of the dot when the function invoked.
3.) Explicit Binding - By using certain methods like `.call()` we can explicitly pass in as an argument when we want 'this' to refer to.
4.) New Binding - Using a constructor function with the 'new' keyword points 'this' to the newly created object. For example when we have a function that takes keys as parameters, we can construct an object and refer back to the keys we made with 'this'. Then all we have to do construct our new object calling the function with the 'new' keyword, and 'this' remembers the keys, and we just set our values for those keys.

5. Why do we need super() in an extended class?
Answer: Super() is used to access and call functions on an object's parent.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your repo to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/master; your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://bloomtech.notion.site/bloomtech/BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) (see part 2, submitting an assignment with codegrade).
