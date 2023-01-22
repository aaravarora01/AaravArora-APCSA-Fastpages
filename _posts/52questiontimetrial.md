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

Consider the following instance variable and methods. You may assume that data has been initialized with length > 0. The methods are intended to return the index of an array element equal to target, or -1 if no such element exists.

For which of the following test cases will the call seqSearchRec(5) always result in an error?
I. data contains only one element.
II. data does not contain the value 5.
III. data contains the value 5 multiple times.

- I chose I only which is incorrect since I will return the correct value of target and 0. The correct answer is II only since it will cause an ArrayIndexOutOfBoundsException since a negative value is entered into the array.

### Question 23 ###

Consider the following instance variable and method.

Assume that animals has been instantiated and initialized with the following contents.

What will the contents of animals be as a result of calling manipulate?

I chose answer E because I forgot to account for the fact that k is equal to the size of the array of animals minus 1, which if I had accounted for, I would have gotten the correct answer of B. In the future, I'll make sure to read questions over again to make sure that I properly understand what the question is asking for especially on difficult questions.

### Question 29 ###

Consider the following code segment.

```
for (int k = 1; k <=100; k++)
    if ((k % 4) == 0)
        System.out.printn(k);
```

Which of the following code segments will produce the same output as the code segment above?

I chose answer D which is incorrect since it will only multiply by 4 which will print out 4, 16, 64. However, the correct answer is B since it will print 1, 5, 9, 13, etc which is the same as the initial code segment.

### Question 30 ###

Consider the following method.

What value is returned as a result of the call scramble("compiler", 3)?

I choes answer B which was in correct; the correct answer is C. Answer B would be correct if the first call to substring was word.substring(howFar, word.length()). The reason why C is correct is because the class above doesn't use the first character so the correct answer is "ilercom", not "pilercom"

### Question 39 ###
Consider the following recursive method.

```
public int recur(int n) {
    if (n <= 10)
        return n * 2;
    else
        return recur(recur(n/3));
}
```

What value is returned as a result of the call recur(27)?

I chose answer E because I did not account for the fecond call of recur which is why I only returned the recur value for recur(27), not per what the method showed where it ran the code twice. The correct answer should've been 16.