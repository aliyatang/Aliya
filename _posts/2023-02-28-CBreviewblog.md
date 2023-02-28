---
toc: true
layout: post
description: Collegeboard requirements project explanation
categories: [markdown, week24]
title: Collegeboard Requirements Guide for Review
---
## Video Guide
[Click Here](https://youtu.be/GaTUvSp2Wic)

## Purpose and Function
The purpose of this feature is for users to be entertained and improve their English vocabulary skills as they play a word guessing game. It functions by taking the 5 letter input of the user, and outputting different colors to indicate the similiarity of the input with the correct answer. Users can also document their wordle scores to compare their scores with others on the leaderboard, and delete with a pin authentification if needed. 

### Input and Output
The input of the program is in two main different forms, there is an input for the wordle 5-letter word. If there is an input which is a not 5 letters and/or a real word, an error message pops up. The output is the score updating, and the letters of the gussed word changing color according to the unknown correct word. Green indicates that the respective letter is in the right spot, yellow indicates that the letter is in the word but not in the right spot, and grey means that it is not in the word at all. There is also the input for multiple attributes (name, pin, score) by submitting text into inputs on the frontend. The output is an error alert if the fields are not filled in correctly, or the presence of the submission input in the frontend database table. 

## Data Abstraction
![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/23-02-28-pic1.png?raw=true)
The list "WORDS" is shown above, it contains all the possible words that could be randomly selected as the unknown correct guess.

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/23-02-28-pic2.png?raw=true)
Here is the list "WORDS" being used to randomly select the unknown correct. 

## Managing Complexity
The code segment above show sthe list "WORDS", which manages complexity int he program as it contains thousands of words in one location variable. The list is needed, as without it, all the variables would be stored into seperate variables which would result in thousands of different variables. That is very impractical and hard to manage in comparison to stroing the words all in one list location. 

## Procedural Abstraction
![This is an image]()
This code segment shows the algorithm for function "shadeKeyBoard" with the parameters "letter" and "letterColor".

![This is an image]()
 The "shadeKeyBoard" function is being called within another function, when the letter in the guessed words similarity with the actual word is found.

"shadeKeyBoard" contributes to the overall function as the program, as it allows for the users inputted guess to be checked to see the similarity between the actual unknown word to be guessed by letting the letter box color be outputted and updated in the keyboard. This allows for the user to easily see what letters have already been guessed and what the status of each of their letters is in the keyboard on the user interface. Overall, it makes it much easier and more efficient for the user to play the game and for it to continue on. 

## Algorithm Implementation
The function "shadeKeyBoard" contains iteration (for loop), sequencing and selection (if statements). First, it uses a for loop to iterate through each of the keyboard buttons on the user interface. For each button, it uses sequencing with the if statements to check if the letter on the keyboard is equal to the one that is entered and being checked. Selection as it only allows for the program to continue on if this condition is met. If this condition is met, more if statements check the color of the keyboard letter to see if it needs to be updated. The first if sttaement is if the "oldColor", or previous color of the keyboard letter equals green. If it is green, the keyboard letter color will still remain green. Next, if the "oldColor" equals yellow and the new color isn't equal to green, it returns yellow and the keyboard letter color remains yellow.

## Testing
First call:
"shadeKeyBoard" is called when the user presses enter and the keyboard buttons check the letters they enter, using the "letter" parameter.

Second call: 
"shadeKeyBoard" is called when the user presses enter and the boxes need to be reshaded as they got new letter colors. Specifically, if the first letter color is yellow and now the correct letter is in the correct spot, using the "color" parameter. 

Condition(s) tested by first call:
The first call tests to see what letters are guessed and where they may possibly be need to be updated on the user interface keyboard. 

Condition(s) tested by the second call: 
The second call tests to see if the old color of the keyboard letter is yellow and if the new color isn't green. 

Results of the first call:
The letters from the user's guess is tested, allowing for the correct letters color boxes to be tested and updated. The accuracy of each letter from the users guess can be updated.

Results of the second call:
The accuracy and the similarity of the letter is tested. The previous color of the specific key is yellow, and remains yellow, allowing the status of this specific letter to be accurate and updated for the user. 