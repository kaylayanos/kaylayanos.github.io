---
layout: project
type: project
image: img/database-project/database1.png
title: "Bank Database Project"
date: 2023
published: true
labels:
  - C
  - C++
summary: "Created a simple bank database and interface for my ICS212 class."
---

## The Task
For my ICS212 class, we had a project where we had to create and implement a database and interface for a bank application. The user was suppose to be able to add, delete, list all, and find information from the database. We were also tasked to find a way to store the data into a txt file, so when you run the program again, the data from when you last ran the program was in the database when you ran it again. In addition to that, we were tasked to create "debug mode" where when you compile the program, if you add the additional words debug into the terminal, it would run the debug version using global variables. This project was done twice, first in C, then in C++.

## Challenges
Out of all the assignments in this class, this would be the most challening. I struggled a lot in trying to find a way to make a writeFile and readFile function so that when you exited the program, everything in the database was transferred to a txt file and when you ran the program, the program would read the txt and transfer everything into the database.

## Overall
Overall, from this project, I was able to understand how pointers in C work. I was able to implement them and in the end, was able to complete everything including the writeFile and readFile functions. This project not only taught me implementation and code, but it also help me realize how bad my study/work habits were. The first project was to implement this code in C and like most college students, I procrastinated. In the end, I was able to finish it, but there were some errors with the writeFile and readFile functions. However, we did get a chance to write the code again, but in C++. This time I knew what to expect and set times to sit down and work. This helped me a lot because in the end, I was able to manage my time and completed and got everything to work!

Here is a snippet of code for one my functions:
```c
int findRecord(struct record *start, int uaccountno)
{
    struct record *temp = start;
    int value;
    value = 0; /* 0 -> failed, 1 -> success */

    if (debugmode == 1)
    {
        printf("FIND RECORD FUNCTION CALLED\n");
        printf("ACCOUNT NO TO FIND: %d\n", temp->accountno);
    }

    do
    {
        if (temp->accountno == uaccountno)
        {
            printf("Account number: %d\n", temp->accountno);
            printf("Name: %s\n", temp->name);
            printf("Address: %s\n", temp->address);
            value = 1;
        }
        temp = temp->next;
    } while (temp != NULL);

    if (value != 1)
    {
        printf("No records found.\n");
        value = 0;
    }

    return value;
}
```
