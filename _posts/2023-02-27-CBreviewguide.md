
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
![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/Screen%20Shot%202023-02-28%20at%202.26.50%20AM.png?raw=true)
![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/Screen%20Shot%202023-02-28%20at%202.27.04%20AM.png?raw=true)
This code segment shows the algorithm for the asynchronus function "checkGuess". 

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/Screen%20Shot%202023-02-28%20at%202.31.31%20AM.png?raw=true)
 The "checkGuess" function is being called by the function clickKey, shown above. When the enter key is pressed, it calls "checkGuess" to check the user's inputted guess. 

"checkGuess" contributes to the overall function as the program, as it allows for the users inputted guess to be checked to see the similarity between the actual unknown word to be guessed, and indicates an appropriate response(whether the word is long enough or a real word, or the color of the letter) to be outputted. This allows for the whole wordle game to function and continue on. 

## Algorithm Implementation
The function "checkGuess" contains iteration (for loop), sequencing and selection (if/else statements). First, is uses a if statement, to check if "guessString", the user's inputted guess, is less than 5-letters (sequencing). If this condition is met and the word is not long enough, then the user will be alerted that their input isn't valid (selection). Then, another if statement checks in with a dictioanry API to see if the inputted word doesn't exist in the dictionary (sequencing). If the word doesn't exist in the dictionary, then the user will be alerted that their inputted guessed word is not a real word (selection). Lastly, an else statement is used, which is for a valid input (sequencing). Within this else statement (selection), it uses a for loop (iteration) to check every single letter of the 5-letter inputted word and compares it with the actual correct unknown guessing word and marks an index. It uses a seires of if/else statements based on the position of the letter (sequencing): if the index remains the same and has no change, meaning the letter is not in the word, then the output will be grey, if the indexes are the same, then that means the letter is the right spot and the letter color outputted is green, and lastly an else statement is used for the remaining options, which means that the letter is in the word but not in the right spot and the letter color outputted should be yellow (all sequencing and selection). 

## Testing
First call:
"checkGuess: is called when the user inputs their first guess, with the arugment being the first 5-letter word inputted as a guess and it is compared to the actual unknown word. 

Second call: 
"checkGuess" is called at the end of the program for the 6th guess, and if the final guessed word is incorrect, the user will be alerted with the correct word. 

Condition(s) tested by first call:
The first call tests to see if the users inputted first guess matches the actual unknown word and how similar it is. Each letter of the word is compared with the actual word to see it's position and accuracy. 

Condition(s) tested by the second call: 
The second call tests to see if the users inputted last (6th) guess matches the actual unknown word and how similar it is. Each letter of the word is compared with the actual word to see it's position and accuracy. 

Results of the first call:
The accuracy and similarity of the first guess with the actual word is shown each of the letters changing color to green, yellow, or grey to display the accuracy of each letter. If the guess is completely correct, a message is displayed that the user won. all the letters will be green, and the program ends. if the guess does not completely match the word, then the program will continue and the user will continue to enter their next guess.

Results of the second call:
The accuracy and similarity of the last (6th) guess is compared to the actual word and displayed using the colored letters. If the last guess is completely correct, a message is displayed that the user won and the actual unknown word will be displayed. 