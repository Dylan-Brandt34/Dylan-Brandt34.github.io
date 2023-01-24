---
layout: post
title: 'Sudoku Puzzle Solver'
---
## Introduction ##
Before I started development on the soduku solver, there were two things that I knew I wanted to familiarize myself more with. 
- 1.) The Python Programming language 
- 2.) Unit testing 

Because of how much talk there has been the past few years regarding *Python*, I knew that I needed to give myself some more exposure to the language. Unit testing has always been something I've used from time to time in school and also in my current job, but I felt like building a project from the ground up while utilizing unit tests would help me understand the importance of the tool. When browsing sources for potential personal projects, a sudoku solver program was listed on a few sites. I personally enjoy solving sudoku puzzles, so I thought that it would be a great option for my first personal project. 

## Getting Started ##

I began a few rough outlines of how the flow of my program should be performed [ shown below ] 


### ---------------- Put draft photos here -------------------- ###
{% image="projects/sudoku/more refine sudo code .png" %}
{% include image.html url="http://www.gratisography.com" image="projects/sudoku/Rough draw up of Sudoku plan.png" %}

These documents helped me find a starting point with my program and that was to first get the soduku puzzle stored in a way for the program to solve the puzzle. *It should be noted that although there is **alot** of sources online regarding how to build this program, I decided it would be in my best interest to design and build this program myself and then go about optimizing the project*. 

## Custom Data Types ## 

My thought process of how to go about solving a sudoku puzzle would turn a 2D array consisting of numbers and *blanks* into a 2D array of "Item" objects. The item class is shown below and is a very simple data type consisting of: 
- A value (either a number or blank string)
- A boolen called "editable" that is only true if item's constructor was sent an empty string. 

### Show Item Class Definition Here ###






