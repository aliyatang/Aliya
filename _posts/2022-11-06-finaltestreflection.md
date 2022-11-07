---
toc: true
layout: post
description: Questions I got wrong for the final 50 question test
categories: [markdown, week12]
title: Final Test Reflection
---
Results:
![This is an image]()

## Q13 Test cases for allPositive in a list
![This is an image]()
Answer A doesn't encounter a positive number, therefore it reutnrs the intended answer. The correct answer is C, because the procedure traverses this list and eventually encounters the positive value 1. At this point, the procedure returns true when it should return false because the list does not contain only positive values.

## Q30 Benefit of using a list when rounding
![This is an image]()
For Answer A, the algorithm used to round a numeric value to the nearest integer will be the same regardless of whether the value is stored in a list. The correct answer is B, because using a list as a data abstraction can result in a program that is easier to develop and maintain. It is easier to apply the same algorithm to every element in a list than to apply the same algorithm to many separate variables.

## Q36 Store even numbers in evenList
![This is an image]()
Answer B is incorrect, because it generates the list [3, 5, 7, 9, 11, 13, 15, 17, 19, 21] since i is initialized at 1. Answer C is correct, becaue for the first iteration of the loop, twice the value of i, or 2, is appended to evenList, and then i is incremented to 2. For the second iteration of the loop, twice the value of i, or 4, is appended to the list, and then i is incremented to 3. This continues eight more times, appending the next eight even numbers to evenList. This code segment will generate the list [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]