---
layout: essay
type: essay
title: "Smart Questions and Not so Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-05
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

## What Makes a Question, Smart?
When asking a question, it is important to ask it a smart question. What does that mean? First, to make a smart question it must have a purpose. Smart questions have a clear purpose or goal. They are asked with certain objective in mind. The question needs to be clear, specific, and well-structured. They cannot have a lot of ambiguity and vagueness. If someone were to ask you, “I am getting an error in my code. Can someone help me?” There are a lot of follow up questions you would need to ask to properly answer this like  “What did you put that is resulting in the error that you are getting?” Smart questions are usually very specific which helps the person asking the question as they are more likely to get an answer that is beneficial to them. 

When asking a question, it is helpful to both the person asking the question and the person answering the question to provide context or even a snippet of your code. An example would be, “I am trying to use a for loop to print out the numbers in my array, but when I run my code, I get, ‘Exception in thread “main” java.lang.ArrayIndexOutOfBoundsException. This is a snippet of my code:”
```java
int arr[] = {1, 2, 3};
for (int i = 0; i <= arr.length; i++)
	system.out.println(arr[i]);
```
Now, when someone reads the question and can visually see what was written in the code and can provide specific feedback that is more meaningful to the person who asked the question. 

## Why Smart Questions are Important
Asking smart questions are especially important for smart software engineers because their smart questions can lead to better solutions. The smart questions can help break down the problem into more smaller and manageable pieces for them to work on. The questions can also lead them to see the problem in a different angle which can lead them to a more efficient solution.

## Example of A Smart Question from Stack Overflow
When looking through some examples of a smart question on stack overflow, I found this one where the person asking the question asks “Which equals operator (== vs ===) should be used  in JavaScript comparisons? You can find the question [here](https://stackoverflow.com/questions/359494/which-equals-operator-vs-should-be-used-in-javascript-comparisons), just by looking at the question, it is short and straight to the point. Also, when you open the link, there are a few follow up questions like “Is there a performance benefit to replacing == with ===?” and “If no type conversion takes place, would there be a performance gain over ==?” The responses that this question got was very informative as it answered the main question and gave some information about the follow up questions the person had. The person that responded to the question also put a table to that compares the different inputs and weather it would be true or false if they used the == ot ===. An example from the table:
```
x = 0, y = false
(x == y) – true
(x === y) – false
```
In addition to the answer, it was able to start a conversation about special cases. 

## Example of a Not so Smart Question from Stack Overflow
Although stack overflow has a lot of smart questions that are being asked, there are also a lot of questions that are not so smart or could use some improvement. I found this question called “Get month name from Dat. You can find the question [here]( https://stackoverflow.com/questions/1643320/get-month-name-from-date). First, the title of the post is not a question. If you want to answer this question you would have to click on it and open the full post to see the question, which is “How can I generate the name of the month (e.g: Oct/October) from this date object in JavaScript?” The person who asked the question provided:
```javascript
var objDate = new Date(“10/11/2009”)
```
Although this is enough context to get a sufficient answer, there were no conversation or explanation to the solution. The answer was just given. That is fine, however, when you ask smart question, you are supposed to gain the answer and more insight to why that was the answer.  


