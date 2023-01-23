---
toc: true
layout: post
description: Becoming more familiar with debugging.
categories: [markdown, week 19]
title: Debugging
---
# What is debugging?
Debugging, in computer programming and engineering, is a multistep process that involves identifying a problem, isolating the source of the problem and then either correcting the problem or determining a way to work around it. The final step of debugging is to test the correction or workaround and make sure it works.

# Why is debugging important?
Debugging is important in programming because it helps ensure that a program is functioning correctly and is free of errors. When a program contains bugs or errors, it can produce unexpected results or crash, which can lead to lost time and resources trying to fix the problem. Debugging allows developers to identify and fix these errors before a program is released, which can improve the overall quality and reliability of the program, and ultimately save time and resources in the long run. Additionally, debugging also helps in understanding the code and how it works, and can also help in finding and fixing security vulnerabilities.

# Common coding errors
Examples of common coding erros include:
- Syntax error
- Runtime error
- Semantic error
- Logic error
- Disregarding adopted conventions in the coding standard
- Calling the wrong function
- Using the wrong variable name in the wrong place
- Failing to initialize a variable when absolutely required
- Skipping a check for an error return

# How to debug
To debug a Python script in VSCODE, you can select the down-arrow next to the run button on the editor and select Debug Python File in Terminal.
![This is an image](https://code.visualstudio.com/assets/docs/python/debugging/debug-button-editor.png)

To debug a web application using Flask, Django or FastAPI, the Python extension provides dynamically created debug configurations based on your project structure under the Show all automatic debug configurations option, through the Run and Debug view
![This is an image](https://code.visualstudio.com/assets/docs/python/debugging/debug-auto-config.png).

To debug other kinds of applications, you can start the debugger through the Run view by clicking on the Run and Debug button.
![This is an image](https://code.visualstudio.com/assets/docs/python/debugging/debug-run.png)

# Basics
Dynamic analysis, execution, stepping, brekapoints and exceptions, modying execution, runtime error debugging, logical error debugging

# Errors I've Run Into
1. Exception has occurred: SystemExit
![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/01-23-23-Screenshot1.png?raw=true)
It would not let me debug, so I tried fixing the error-
First Website Referenced [Click Here](https://stackoverflow.com/questions/52372810visual-studio-code-python-debugging-exception-has-occurred-systemexit)

Tried unchecking Uncaught Exceptions... couldn't find no luck.

![This is an image](https://i.stack.imgur.com/damNF.png)

Second Website Referenced [Click Here](https://github.com/microsoft/vscode-python/issues/3201)