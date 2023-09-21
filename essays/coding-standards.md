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
