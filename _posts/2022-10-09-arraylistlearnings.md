---
toc: true
layout: post
description: ArrayList CB Learnings
categories: [markdown, pbl]
title: Array List CB Learnings
author: Aarav Arora, Braeden Copley, Tigran Arakelov, Vunsh Mehta
---

# Learnings #
FRQ: https://secure-media.collegeboard.org/digitalServices/pdf/ap/ap17-comp-sci-a-q1.pdf

Java uses the notion of a list too. It defines the interface List which is in the java.util package. An interface lets you define a type based on what you want it to do, not how it does it. Several classes can implement the same interface and you can pick the one to use that works best in your situation.

# List Methods on the Exam #

- int size() returns the number of elements in the list
- boolean add(E obj) appends obj to the end of the list and returns true
- void add(int index, E obj) moves any current objects at index or beyond to the right (to a higher index) and inserts obj at the index
- E get(int index) returns the item in the list at the index
- E set(int index, E obj) replaces the item at index with obj
- E remove(int index) removes the item at the index and shifts remaining items to the left (to a lower index)

# Syntax and Learnings #

- It implements the List interface using an array and allows the underlying array to grow or shrink as needed. This also means that the ArrayList class contains the code for the methods defined in the List interface.

- There are actually two different add methods in the List interface. The add(obj) method adds the passed object to the end of the list. The add(index,obj) method adds the passed object at the passed index, but first moves over any existing values to higher indicies to make room for the new object.

- Declare an array using type[] name. Examples are shown below.

