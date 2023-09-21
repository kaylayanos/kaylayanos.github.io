---
layout: essay
type: essay
title: "The Power of Good Coding Standards"
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
function badexample(a) {
let b=0;
let i=0;
while(i<a.length){b+=a[i];i++;}
return b;
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
In this example, the code is so much easier to read. There are indents and spaces between operations. I would rather have this over the first example. When looking at this function, not only does it look better, but it also can be understood much faster. 

However, spaces and indentation does not only mean for good coding standards, but includes clarity and readability, consistency, simplicity, and the one I think is the most important, documentation. 

## Clarity and Readability
By making your code uniform, you are make it clear and readable. This benefits not only yourself, but the people around you. This aspect includes consistent formatting, choice of naming your functions and variables, and more. When you are using consistent formatting, this can include indentation, line length, etc., it makes the code visually cohesive and more understandable. By making meaningful function and variable names, you make it more clear what is going to be put in there, which enhances the code comprehension.

## Consistency and Simplicity
Making your code consistent will make it easier to add on to your existing code. When you make your code consistent, it can reduce the amount of confusion for not only yourself, but for your colleagues as well. In addition to making it consistent, if you make it simple not only will it be easier to understand, but it will also be easier to fix, debug, and maintain.

## Documentation
Documentation might be the most important thing when it comes to coding standards. Documentation helps unsure that the code is understood by others. One important part of documentation is inline comments in the code. The purpose of comments is to explain the logic behind each line, clarifying complex sections, and providing more context to help others understand why it is there. 

Another part of documentation is the file level documentation for larger databases and API documentation. The documentation's purpose is to provide an overview of the file's contents and purpose. This is very crucial because it will be used to guide others who will/potential use your code. 

## Benefits of Good Coding Standards
Other than the benefits I have stated above, I firmly believe that when you code with good coding standards, it could help you with learning a programming language.  When you are learning a programming language before you get into all the algorithms and data structures, you first need to learn the syntax. By writing clean looking code, it allows you to focus on the language's syntax and concepts without being distracted by messy or inconsistent code. When you write code with good coding standards, you are constantly writing cleaner, consistent, and understanding code.

## ESLint
After spending a week of using ESLint with IntelliJ, personally, I like it. I would say that I have pretty good coding standards, but I always knew that I could do better in it. By using ESLint, it allowed me to see which parts were a bit unclear or not consistent. ESLint is very useful because not only does it help with good coding standards, but it also catches a lot of my mistakes such as variable naming. Usually, when I write my code, I get a lot of red "X", however, I find it oddly satisfying trying to fix it and seeing the amount of X's go down to none and seeing the green checkmark.




