---
layout: project
type: project
image: 
title: "Sudoku Solver"
date: 2022
published: true
labels:
  - Java
summary: "I created a Sudoku Solver for one of my homework assignments for ICS211."
---
For this assignment, we were tasked to finish the fillSudoku function that would fill the sudoku table, using recusion. Recursion is one of those topics where it is simple at first, but on a large scale, it gets confusing and complex.

Here is a snippit of my fillSudoku code:
```java
  public static boolean fillSudoku (int [][] sudoku) {
    //1: BASE CASE
    if (SudokuTest.isFilled(sudoku)) {
      return checkSudoku(sudoku, true);
    }
    //2: find next empty cell
    int x = 0;
    int y = 0;
    
  
    for (int i = 0; i < sudoku.length; i ++) {
      boolean done = false;
      for (int j = 0; j < sudoku.length; j++) {
      int cell = sudoku[i][j];
      if (cell == 0) {

        x = i;
        y = j;
        done = true;
        break;
      }
      if (done == true) {
        break;
        }
      }
    }
```
