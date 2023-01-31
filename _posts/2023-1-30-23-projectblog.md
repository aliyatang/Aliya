---
toc: true
layout: post
description: Individual plan for CPT features
categories: [markdown, week 20]
title: Project Blog
---
For the College Board performance task, we need to have a project that meets all the parameters. We also need video demonstration and written response that showcases our program purpose and functionaliy, data abstraction, managing complexity, procedural abstraction, algorithm implementation, and testing. This outline with the college board requirements will help with better planning and make sure that I meet all the requirements. 

# Feature Description
Wordle inspired game

## Purpose and Function
The purpose of this feature is for users to be entertained and improve their English vocabulary skills as they play a word guessing game. It functions by taking the 5 letter input of the user, and outputting different colors to indicate the similiarity of the input with the correct answer. 

# Code Plan

## Data Abstraction
The code uses data abstraction as it stores 5-letter words in a list. These words in the list are used for generating the final correct guessed word, and for words that are valid input guesses for the user.

## Managing Complexity
The list that contains the words allows for all the possible words to be selected for the final correct guess or check if the user guess is a valid word to be stored in one place. Without it, the words would have to all be stored in multiple different variables instead of one place, which is not ideal and impractical. 

## Procedural Abstraction
I will have a procedure that checks how similar the correct word and the inputted user guess is, which overall determines if the user wins or not or what colors should be displayed to indicate the position of that letter. There will be two parameters, one being the correct word, and one being the inputted user guess. 

## Algorithm Implementation
The procedure will use sequencing, selection, and iteration. It will use sequencing to carry out the different checks, first to see if the word is the same, then if the letter is same or in the word, etc. Selection is used: if and only if the word is the same as the final correct word, it will display that the user has won. Iteration will be used as it iterates through each letter to check for the similarity with the final correct word. 

## Testing
The first call will be checking an inputted incorrect word with at least one letter that isn't in the word at all (grey), at least one letter that is in the word but not in the correct spot (yellow), and at least one letter that is in the word in the correct spot (green). The second call will be checking an inputted word that is completely correct and completely matches the final correct word (all green). 