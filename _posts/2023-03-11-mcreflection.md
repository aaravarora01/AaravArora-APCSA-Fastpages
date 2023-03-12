---
toc: true
layout: post
description: My Reflections + Questions that I got Wrong
categories: [markdown, CollegeBoard Learning]
title: 2015 MCQ Exam Learnings + Reflection
author: Aarav Arora
---

# Overall #

**Score: 36/39 = 92.3%**

I scored 36/39 on this exam which I think is a good score and I know what specific areas I need to work on throughout the year. I think that I have a good understanding of most areas but need a bit more review with recursion and reviewing boolean/De Morgan's Laws. These are areas where I plan to do more practice MCs and study more in the future.

### Question 35 ###

![image](https://user-images.githubusercontent.com/45216129/224534279-06e1be70-1feb-44af-8efb-95957b0a9735.png)

This would be the result if mid was calculated as (start + end + 1) / 2. The correct answer is 5. In the first iteration of the binary search, it will check the value at index (0 + 7) / 2 which is index 3. Since 8 is greater than data[3], start is assigned mid + 1 which is 4 and the process will repeat. In the second iteration of the while loop, it will check the value at index (4 + 7) / 2 which is index 5. Since data[5] is 8, 5 is returned.

### Question 36 ###

![image](https://user-images.githubusercontent.com/45216129/224534268-e71ca1e2-5baf-4bea-ad77-bdedbb9b1135.png)

I chose 1,000 which is incorrect. The binary search eliminates half of the array during each iteration. This could be the number of elements left to examine after the first pass.

### Question 37 ###

![image](https://user-images.githubusercontent.com/45216129/224534252-dd26ca05-9d78-4f6d-83db-cc4bf9445caf.png)

I chose choice D which is incorrect. Choice I iterates from startIndex to the end of the array words as expected, but when it adds elements to result it adds the current word followed by a second word starting at the end of the array words. This will result in duplicate words being added to result.  Choice III starts by adding the elements of words to temp in reverse order. The second loop starts at the beginning of temp (which was the end of words) and adds each subsequent element to result until it reaches the element that was at startIndex and is now at temp.length – startIndex resulting in result containing the required elements in reverse order. Instead, the correct answer is II and III.
