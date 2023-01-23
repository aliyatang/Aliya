---
toc: true
layout: post
description: My grading/scoring for the sample preformance tasks submissions
categories: [markdown, week17, week 18, week 19]
title: Preformance Task Scoring
---
# Scoring 1 - Week 17

## Submission 1
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>1</td>
        <td>
            Requirements met - The program has the input of the triangle side lengths and output of the information about the triangle, including classifcation of the triangle, degrees of each angle, trigonemetric values, etc. They also mention the program purpose and functinality, which is to help with information about triangles based on inputted side lengths. 
        </td>
        <td>0</td>
        <td>Requirements not met - The described purpose, to provide information about a triange, is actually the functionality of the program. They only described the functionality and not the purpose. This is something to take note of in my own project, as I feel that purpose and function may be hard to differentiate between if not careful.</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - The program meets the requirements of two code segments. For example, one is how they implement and identify sideIndex, which stores the data of the types of triangle. Second, they use sideIndex in the program to fulfill the program and identify and output what triangle it is based on the input. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>0</td>
        <td>
            Requirements not met - This program does not manage complexity well. In the written response, the code uses a list that has all the classifcations under one variable(sideIndex), when ideally this is not needed because they could just use strings instead of lists. So, their written response explanation does not show how they manage complexity either. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - The student-developed procedure(ratioCalculate) has three parameters that effects how they are ordered for the ratio. This procedure is also being called. They also describe what the procedure does, which is to calcualte the ratio fo the triangle sidelengths to store as values in sideRatio. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - The student developed an algorithm(ratioCalculate) that includes sequencing, selection, and iteration. They also describe how the algorithm works in a lot of detail.
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>1</td>
        <td>
            Requirements met - They describe two calls to the procedure ratioCalculate, the conditions being tested, and the results of each call. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>
</table>

## Submission 2
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>1</td>
        <td>
            Requirements met - The program has an input of the users clicking to result in the outputs, for example the choice to remove tiles on the grid and control the simulation(pause, restart, reset, etc). The program function and purpose are both identified, with the function as an interactive simulation and its purpose as serving entertainment for the user.
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - They store data in several lists, (startGrid, currentGrid, nextGrid) and successfully show and describe that they use these to fulfill the part of the program which is to store data about the cells. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>1</td>
        <td>
            Requirements met - The program shows how the list manages complexity of the data about the cells, and also explains why are list is necessary to manage complexity in this situation as it is the most efficient to have everything in one place. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - They have two program code segments, one that shows the student-developed procedure(replaceList) that includes the two parameters(current, replacement), and also calls the procedure. They also describe the functionality of the procedure, which is to take inputs identifying numbers for two lists and replace have the first replace the second while still being able to recall the previous points. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

        <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - It includes a pogram code segment of a student-developed algorithm, replaceList, which includes sequ4encing, selection, and iteration. They also explain how this algorithm works, which is using if-else statements to see which list should be copied from. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

        <tr>
        <td>6</td>
        <td>Testing</td>
        <td>1</td>
        <td>
            Requirements met - They describe two calls to the selected procedure, one is to reset everything and another is to be used during the main generation to define the current and replacements, the conditions being used in these calls, and the results of each. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>
</table>

Note: Submission 1 is an example of a lacking Create Preformance Task with multiple missing requirements, while Submission 2 is an example of a good one. I could look back on this for reference on mine as it could be very helpful in seeing what should be done and what shouldn't. 

# Scoring 2 - Week 18

## Submission 1
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>0</td>
        <td>
            Requirements not met - In the written response, they identified the wrong input and output. The student said the input was the user getting asked what the animal was, but it should be the user typing in their answer to what the animal was. They said the output was the user typing in the answer, but it should be the screen telling them whether they got the answer right or not based on the what they answered from input. Also, they failed to mention the purpose of the program, only stating that the functionality was to be shown and identifying animals
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>0</td>
        <td>
            Requirements not met - The student identifies the lists "animalImages" and  "animalList" in two code segments but they don't show them using these lists in either of the code segments. They do describe what data is contained in the list though, one is the animal names and one the the picture of the animals corresponding to those names. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>1</td>
        <td>
            Requirements met - They manage complexity well with their list "animaList" and in their written response explain that how the list manages complexity by being able to store the variables.
        </td>
        <td>0</td>
        <td>Requirements not met - The list actually doesn't manage complexity and the code is not complex, and the written response doesn't explain why their code would manage complexity. They only state that a list storing more than one variable makes it shorter and more complex, which is not true.</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>0</td>
        <td>
            Requirements not met - There is a student-devleoped procedure, "evaluateGuess", with the parameter "guess" and them calling this parameter. However, nt he writtten response they don't say how this specific procedure contributes to the functionality, they only say that it determines if the users guess is right or wrong. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>0</td>
        <td>
            Requirements not met - Though they have a student-devleoped algorith, "evuluateGuess", that has sequencing and iteration, a for loop, and selection, if else statement, their response doesn't explain this well in enough detail. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>1</td>
        <td>
            Requirements met - They describe two calls, a right and a wrong call, to the procedure "evuluateGuess", the conditionas being tested, and the results of each call, getting a point or a strike. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>
</table>

## Submission 2
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>1</td>
        <td>
            Requirements met - In the written response, they identify the input and output. The input is the users input of words such as pine and star, and the output is the generation of the poems. They also mention the program purpose and function, the purpose being to explore the users creativity and the function being to generate poems based on the user input. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - The student identifies the list "nounList" in the two code segments and mention how they are called and used in the program in the procedure "selectWord" as parameter "wordList". They also identify what is being stored in the list, which are the nouns that should be in specific locations in the poem so the poem is in an order that makes sense. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>1</td>
        <td>
            Requirements met - In the repsonse they explain how the code uses lists of words to manage complexity. They say that they need this list because it can randomly select multiple nouns at once and store all of them in one list instead of multiple variables. They also say that they need this list otherwise they would have to find another way to randomize selection and the code would be very unorganized. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - There is a student-devleoped procedure, "createPoems", with the multiple, four, parameters that are used. They also show how this procedure contributes to the overall function by putting the final selection of the poems together and stating that is in relation with the user inputs based on how many the user inputted and if they wanted articles in the poems. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - They have a student-devleoped algorith, "createPoems", that has sequencing and iteration, a while loop, and selection, an if else statement, and their response explains this well in enough detail. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>1</td>
        <td>
            Requirements met - They describe two calls, "createPoems(nounList, verbList, adverbList, 1)" and "createPoems(nounList, verbList, adverbList, 0)", on what they do, checking "aSetting" in different ways, and the results of each call, generating peosm from "aritclePoem" or "noArticlePoem". 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>
</table>

## Submission 3
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>0</td>
        <td>
            Requirements not met - In the written response, they identify the input and output. The input is the users selection of the characters from the dropdown box, and the output is the display changing based on the selected character and the winner screen. However, they fail to mention the program purpose and only mention the function, stating that the program aims to the determine the winner of a hypothetical fight. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - The student identifies the list "firstCharacterList" in the two code segments and mention how it is used for the purpose of the program as the first parameter of the function "findWinner". They also identify what is being stored in the list, which are the power rankings and the images for the selected character. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>1</td>
        <td>
            Requirements met - In the repsonse they explain how the code uses lists of ranking and images to manage complexity. They say that they need this list because it allows for information about the character to be stored in one variable instead of multiple to hekp organize and shorten the code needed for the program. They also explain that without it, there would be many parameters needed for "findWinner" function. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - There is a student-devleoped procedure, "findWinner", with the multiple, two, parameters that are used and they show that they call this procedure. They also show how this procedure contributes to the overall function by stating that the function takes in the characterList to compare the ranings and find the winner. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - They have a student-devleoped algorithm, "findWinner", that has sequencing, if else statement, and iteration, a for loop, and their response explains this well in enough detail. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>1</td>
        <td>
            Requirements met - They describe two calls, one that uses the arguments Vision and Bishop and another that uses the arguments Carnage and Venom. They also show what is tested by each call, the different parts of the if else statement, and the results of each call, the different displays of image and text of who won. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>
</table>

## Submission 4
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>1</td>
        <td>
            Requirements met - In the written response, they identify the input and output. The input is the users clicking buttons and inputting/entering words into the text box, and the output is the color scheme of the inputted letters to be displayed. They also mention both the function, which is to have users guess 8 letter words, and the purpose, to challenge the player. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>0</td>
        <td>
            Requirements not met - The student identifies the list "guesses" in the two code segments and show the storage of data in this list, but fail to show them using the data in this list.
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>1</td>
        <td>
            Requirements met - The program has the list "guesses" in the code segment and it helps manage complexity by counting the number of guesses, and they also explain why they need this because they need to know when the program ends, when the user guesses six times, or else it will continue forever.
        </td>
        <td>0</td>
        <td>Requirements not met - The program has the list "guesses" in the code segment but it doesn't manage complexity as just counts. They also don't explain how it manages complexity, because they just say that the guesses functon is to stop the program when the user has guessed six times when they could just use a counter. </td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - There is a student-devleoped procedure, "isitcorrect", with one parameter, "checkanswer" that is used and they show that they call this procedure in the second code segment with the argument "answer". They also show how this procedure contributes to the overall function by stating that procedure ehelps determine if the answer matches the correct word of letter position for the user input. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - They have a student-devleoped algorithm, "isitcorrect", that has sequencing and selection, if else statement, and iteration, a repeat loop, and their response explains this well in enough detail. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>0</td>
        <td>
            Requirements not met - They describe two calls, one that has both the right letter and rigt position and another that has the right letter but wrong position. They also show thhe conditions and the results of each call, the color changing of the letter. However, these calls cause the same segment of code in the algorithm to execute. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>
</table>

# Scoring 3 - Week 19

## Submission 1
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>1</td>
        <td>
            Requirements met - In the written response, they identify the input and output. The input is the users choice of rock paper, or scissors, and the output is if they win, lose, or draw. They also mention the program function and purpose. The function is said to be to output the relationships of the diffferent combinations of rock paper and scissors, and the purpose is said to be entertainment and can be used to make a decision for the user.
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - The student identifies the list "RPS" in the two code segments and mention how it is used for the purpose of the program to determine what combinations of rock papers and scissors wins/loses/draws. They also identify what is being stored in the list, which are rock paper and scissors. 
        </td>
        <td>0</td>
        <td>Requirements note met - The student met all the requirements except for the second segment does not show data being accessed from the list. They do not reference the RPS list at all.</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>0</td>
        <td>
            Requirements not met - In the repsonse they show the list "RPS", but this list doesn't manage complexity in the program. They can achieve the same thing without the list by putting the values directly into "cpuPlay". They say that they need this list because the program can only function with the list "RPS", without it, each potential computer input would need to responc to a number and then it would pick a number. However, this would work just as well, showing that they don't need list "RPS".  
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>0</td>
        <td>
            Requirements not met - There is a student-devleoped procedure, "rpsGame", with the one parameter that is used and they show that they call this procedure. However they don't explain how this procedure contributes to the overall function, they only state that it allows for hte program to execute smoothly. . 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - They have a student-devleoped algorithm, "rpsGame", that has sequencing, if else statement, and iteration, recursion, and their response explains this well in enough detail to be recreated. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>1</td>
        <td>
            Requirements met - They describe two calls, one that uses uses "yourPlay" with value "Rock" and computer input "Paper", and another that uses "yourPlay" with value "Paper" and computer input "Rock". They also show what is tested by each call, the different parts of the if else statement seeing the combinations of Rock and Paper, and the results of each call, the display of "You Lose" or "Your Win". 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>
</table>


## Submission 2
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>1</td>
        <td>
            Requirements met - In the written response, they identify the input and output. The input is the users choice of rock paper, or scissors, and the output is if they win, lose, or draw. They mention the program function, to input letters and output the letter wehre it belongs in a randomly generated word, and the purpose, to expand the users vocab and let them recognize new words. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - The student identifies the list "letOfGuessWord" in the two code segments and mention how it is used for the purpose of the program as data is being taken from the list in the for loop. They also identify what is being stored in the list, which is the indivdual letters of the word that the user tries to guess.
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>1</td>
        <td>
            Requirements met - In the repsonse they explain how the code uses lists to store the letters of the word to manage complexity. They say that they need this list because otherwise the code would be very inefficient becasue there would have to be 5 new variables ot be stored in the individual letters, which would also make the loop more complicated. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - There is a student-devleoped procedure, "guessWords", with one parameter that are used and they show that they call this procedure. They also show how this procedure contributes to the overall function by stating that a letter will pop up in the space or it will take a life away from the user. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - They have a student-devleoped procedure, "guessWords", that has sequencing, if else statement, and iteration, a for loop, and their response explains this well in enough detail to be recreated, explaining both the if else statement and foor loop and what they do. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>1</td>
        <td>
            Requirements met - They describe two calls, one that uses input of "1" and one of letter "h" by the user and guesses "hello". They also show what is tested by each call, how "1" is not in "hello" and "h" is in "hello", and the results of each call, saying the first call is false and the second call is true. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>
</table>

## Submission 3
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>1</td>
        <td>
            Requirements not met - In the written response, they identify the input and output. The input is the users choice of the state, and the output is the the general information about that state. They also mention both the function and the purpose. The function is to hprovide the user with information about a U.S. state, and the purpose is to help the user with memorzation or just be used to learn something new. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>0</td>
        <td>
            Requirements not met - The student identifies the list "stateList", but it is not shown to be used in either of the two code segments. They do mention how it is used for the purpose of the program as it contains the general information about the state. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>0</td>
        <td>
            Requirements not met - In the repsonse they explain how the code manages complexity. They say that they need this list because, but they don't explain why their code needs a list. They only say that it would be very inefficient and take a long time to run, which is very vague. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>0</td>
        <td>
            Requirements not met - There is a student-devleoped procedure, "updateScreen", but it has no parameter. They also don't show how this procedure contributes to the overall function, they say that the state screen would be updated but the procedure doesn't do that. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - They have a student-devleoped algorithm, "updateScreen", that has sequencing, if else statement. Their response explains it in well enough detail to show how the "updateScreen" algorithm works. 
        </td>
        <td>0</td>
        <td>The procedure "updateScreen" does not include iteration, and it only partiall explains how the alrogthm "updateScreen" works.</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>0</td>
        <td>
            Requirements met - They describe two calls, one that calls "stateInput" to update the screen by pressing the go button and another that calls "stateInput" to display more information by prssing the drop down. They also show what is tested by each call, the display of information for the desired state and the extra information. 
        </td>
        <td>0</td>
        <td>They actually described two calls FROM the prodcedure instead of two calls TO the procedure, and they don't have a prarmeter. They weren't supposed to describe two sepearte operation being preformed, they were supposed to do onditions being tested by the given parameter. </td>
    </tr>
</table>

## Submission 4
<table>
    <tr>
     <th>Row</th>
     <th>Category</th>
     <th>My Score</th>
     <th>Score Reason</th>
     <th>CB Score</th>
     <th>Score Discrepancies</th>
    </tr>
    
    <tr>
        <td>1</td>
        <td>Program Purpose and Function</td>
        <td>1</td>
        <td>
            Requirements met - In the response, they identify the input and output. The input is the users pressing the 'a','d', spacebar, etc keys, and the output is the boat's movement, They also explain the function and urpose of the program, the function is to control the gameplay of the boat with keys, and the purpose is to lessen boredom fot he user.  
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>2</td>
        <td>Data Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - The student identifies the list "fishtypes" in the two code segments and mention how it is used for the purpose of the program as data from the list is accessed in a loop. They also identify what is being stored in the list, which is the type of fish and the number of a specific fish caught. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Managing Complexity</td>
        <td>1</td>
        <td>
            Requirements met - In the repsonse they explain how the code uses a list of lists to manage complexity. They say that they need this list because it allows for more fish to be added to the data list instead of making new variables every time. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Procedural Abstraction</td>
        <td>1</td>
        <td>
            Requirements met - There is a student-devleoped procedure, "clone+movment+range", with the multiple, five, parameters that are used and they show that they call this procedure. They also show how this procedure contributes to the overall function by stating that that procedure determines wehre the clone of a sprite spawns, the movement, and where it goes, allowing for the program of catching a fish to be more challenging. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>5</td>
        <td>Algorithm Implementation</td>
        <td>1</td>
        <td>
            Requirements met - They have a student-devleoped algorithm, "clone+movement+range", that has sequencing, if else statement, and iteration, a for loop, and their response explains this well in enough detail to be recreated. 
        </td>
        <td>1</td>
        <td>None</td>
    </tr>

    <tr>
        <td>6</td>
        <td>Testing</td>
        <td>0</td>
        <td>
            Requirements not met - They don't describe the two calls, they just explain what types of call they are. They dno't explain the conditions, either, they just say what is tested by the calls. 
        </td>
        <td>0</td>
        <td>None</td>
    </tr>
</table>

## Summary/Takeaways: 
From these four submissions, something I noticed was how important the written response is. Previously, I thought that you should put most of the effort into the actual program and video. However, upon reviewing this weeks and past submissions, I realize that many people did have correct code but they didn't get the point because their written response didn't meet the requirements. When doing my written response, I think it would not only be helpful to check in with the college board criteria, but also for me to reference both the submissions who got the point and those who didn't, to see what I should and shouldn't do. 