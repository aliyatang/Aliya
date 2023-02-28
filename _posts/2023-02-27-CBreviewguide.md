
---
toc: true
layout: post
description: Collegeboard requirements project explanation
categories: [markdown, week24]
title: Collegeboard Requirements Guide for Review
---
## Purpose and Function
The purpose of this feature is for users to be entertained and improve their English vocabulary skills as they play a word guessing game. It functions by taking the 5 letter input of the user, and outputting different colors to indicate the similiarity of the input with the correct answer. Users can also document their wordle scores to compare their scores with others on the leaderboard, and delete with a pin authentification if needed. 

### Input and Output
The input of the program is in two main different forms, there is an input for the wordle 5-letter word. If there is an input which is a not 5 letters and/or a real word, an error message pops up. The output is the letters of the gussed word changing color according to the unknown correct word. Green indicates that the respective letter is in the right spot, yellow indicates that the letter is in the word but not in the right spot, and grey means that it is not in the word at all. There is also the input for multiple attributes (name, pin, score) by submitting text into inputs on the frontend. The output is an error alert if the fields are not filled in correctly, or the presence of the submission input in the frontend database table. 

## Data Abstraction
![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/23-02-28-pic1.png?raw=true)
The list "WORDS" is shown above, it contains all the possible words that could be randomly selected as the unknown correct guess.

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/23-02-28-pic2.png?raw=true)
Here is the list "WORDS" being used to randomly select the unknown correct. 

## Managing Complexity
The code segment above show sthe list "WORDS", which manages complexity int he program as it contains thousands of words in one location variable. The list is needed, as without it, all the variables would be stored into seperate variables which would result in thousands of different variables. That is very impractical and hard to manage in comparison to stroing the words all in one list location.

## Procedural Abstraction


