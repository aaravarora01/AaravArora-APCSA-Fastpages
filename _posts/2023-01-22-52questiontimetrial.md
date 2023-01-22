---
toc: true
layout: post
description: My Reflections + Questions that I got Wrong
categories: [markdown, CollegeBoard Learning]
title: 52 Question Exam Learnings + Reflection
author: Aarav Arora
---

# Overall #

I scored 47/52 on this exam which I think is a good score and I know what specific areas I need to work on throughout the year. I think that I have a good understanding of most areas but need a bit more review with 2D arrays and array lists. These are areas where I plan to do more practice MCs and study more in the future.

### Question 6 ###

![image](https://user-images.githubusercontent.com/45216129/213906466-f0481879-e0bc-4053-929b-871d9cac7282.png)

- I chose the option for The row index of an element with the largest value in the two-dimensional array, but the correct answer was the one for the column index. The algorithm uses a for-each loop to traverse the rows, so the row index is not being stored and instead I realized that the column index is being stored in this question.

### Question 7 ###

![image](https://user-images.githubusercontent.com/45216129/213906517-697869a9-f76b-4c65-a9cf-0fd1a638546c.png)

I chose answer C because I accounted for the question having a 1 at the end of each string, when there was actually a 0 at the end of each string. I should've been more careful in reading this question and chosen the option with a 0 at the end.

### Question 39 ###

![image](https://user-images.githubusercontent.com/45216129/213906545-e852f0f5-fe1f-4a6a-a44b-021776caacc2.png)

I chose the answer that the code segment returns a list with fewer elements than intended because it fails to consider the last element of myList. However, this option is incorrect because the code segment returns a list with the right amount of elements intended because it has a for loop that continuously checks. The actual mistake is that the code segment skips some elements of myList because the indexes of all subsequent elements change by one when a list element is removed.

### Question 40 ###

![image](https://user-images.githubusercontent.com/45216129/213906591-ff0a8ebe-fca6-4e83-9a5d-21115d463b64.png)

I was unsure about this question and guessed on it. However, option 3 is the only correct answer because it checks the entire list and removes elements which satisfies the conditions of the code segment. 

### Question 48 ###

![image](https://user-images.githubusercontent.com/45216129/213906620-9e9ee0c5-9c31-4893-b2f5-25d0bea4f2a2.png)

I chose answer E for this question which was incorrect. The code segment uses an enhanced for loop to traverse the valueList array. The statement inside the loop calls the getNum method to access the num instance variable. Thus, option three cannot be correct. The code segment causes a compilation error because the getNum method must be called using the dot operator, not by passing the object reference as an argument.
