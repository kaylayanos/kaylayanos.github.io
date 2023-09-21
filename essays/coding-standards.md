---
layout: essay
type: essay
title: "Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2023-09-20
published: true
labels:
  - Coding Standards
  - Software Engineering
---

One of the many forgotten, but important aspects of coding is coding standards. Many people overlook coding standard because many might think that it is just indents, the placement of curly braces, etc. However, it can be the one difference that can make a significant impact on your software engineering journey. The purpose of coding standards is to design a thoughtful and uniform appearance to your code. 

## Bad Coding Standards

As an example, look at this code:
```javascript
function badexample(nums) {
let total=0;
let i=0;
while(i<nums.length){total+=nums[i];i++;}
return total;
}
```

This code is simple enough where you can still understand what the function is doing. However, you can easily spend unnecessary time trying to understand it due to how low the readability is. 

## Real World Situation
In the real world as a software engineer, you are most likely going to write more complex code with many variables and functions. If you write you code with poor coding standards, it can become very difficult to keep track and make sure all the variables and functions are working the way they are supposed to. If you are having a hard time doing this because of your poor coding standards, it can drop your productivity and work flow resulting in poor work performance. In addition to this, throughout the years you might change employers. If you leave your current workplace with code with poor coding standards, the new person that took your place will have no idea what you were trying to do. It would take them a while to figure out and understand what you were trying to do.

## Good Coding Standards
Here is an example of good coding standards:
```javascript
function goodExample(nums) {
  let total = 0;
  let i = 0;
  while (i < nums.length) {
    total += nums[i];
    i++;
  }
  return total;
}
```
In this example, the code is so much mor easier to read. There are indents and spaces between operations. I would rather have this over the first example. When looking at this function, not only does it look better, but it also can be understood much faster. 

However, spaces and indentation does not only mean for good coding standards, but includes clarity and readability, consistency, simplicity, and the one I think is the most important, documentation. 

## Clarity and Readability
By making your code uniform, you are make it clear and readable. This benefits not only yourself, but the people around you. This aspect includes consistent indentation, choice of naming your functions and variables, and more. 

## Consistency and Simplicity
Making your code consistent will make it easier to add on to your existing code. When you make your code consistent, it can reduce the amount of confusion for not only yourself, but for your colleagues as well. In addition to making it consistent, if you make it simple not only will it be easier to understand, but it will also be easier to fix, debug, and maintain.

## Documentation
Documentation might be the most important thing when it comes to coding standards. 
