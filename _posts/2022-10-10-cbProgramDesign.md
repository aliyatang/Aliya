---
toc: true
layout: post
description: Program Design Questions and Pictures
categories: [markdown, week6]
title: College Board Project Program Design
---
## Group Roles
Sreeja Gangapuram: Scrum Master

Ananya Gaurav: Dev Operator

Aliya Tang: Frontend Developer

Claire Chen: Backend Developer

## General Plan
- Project Plan: Word Nerd
- Student need and purpose: entertainment, fun way to increase student vocabulary (Educational Study or Simulation)
- Student interest: we all play wordle and find it very fun and sometimes challenging. However, as avid wordle players, we find things that we would want to improve about the game and in our version of wordle we will work to provide features to make the game more enjoyable.
    - Hints
    - Indicating colors
    - Warnings for when you use letters that have already shown themselves to be wrong
    - Mainly 6 letter words instead of 5 letter words like wordle

## College Board Requirements

### Program Purpose and Function
Input: 6 letter word
Output: color code the letters to show:
Which letters are in the word?
Which letters are in the word and in the right place?
Which letters are not in the word?

### Data Abstraction
Data of different 6 letter words, and possibly different amount of letters, what genre they belong to, etc, stored in dictionary which is retrieved using API to generate games

### Managing Complexity
Function to read user input and check to see if the word inputted mathces with the word chosen to be guessed, seeing which of the inputted letters are in the words or not in the word, and which letters are in the right spot or in the wrong spot

### Procedural Abstraction
By comparing user input to the word, retrieve data from dictionary about the word

### Algorithm Implementation
Develop algorithim to count number of words/tries are inputted to display at the end screen of results. 

### Testing
Input multiple words, test if all the functions are correct: certain colors displayed for letters, display the right word, etc.  Ask multiple people to test out the wordle and give feedback on what to fix or suggestions to improve it. 

## User Interface
Background color: light blue
Letters that are in the word and are in the right place-: Light green #a8e2b2
Letters that are in the word but not in the right place: light yellow
Letters that are wrong: Light gray
Data in program:
list of 6 letter words to generate games

## Requirements
Finish by the begining of November, which gives us the month of October (3 weeks)
What we are being graded on: college board requirements - Data Abstraction, Managing Complexity, Procedural Abstraction, Algorithm Implementation, Testing