---
toc: true
layout: post
description: Created Methods and Class FRQ
categories: [cb]
title: 2023 FRQs
author: Aarav Arora
---

## Methods FRQ
This question involves calculating the sum of a given set of integers. In this question, you will be required to write two methods of the Sum class.

```java
public class Sum {

    /** Returns the sum of all even integers between 1 and endInt, inclusive */
    public int getEvenSum(int endInt) {
    { /* implementation not shown */ }
    /** Returns true if the result of getEvenSum is greater than a random value, otherwise returns false */
    public boolean sumComparison(int endInt) 
    { /* implementation not shown */ }
    }
}
```

### Methods FRQ Part A
Write the getEvenSum method which returns the sum of all even integers between 1 and endInt. endInt will always be greater than or equal to 1. 

The following is an example of the getEvenSum method:
| endInt | getEvenSum return value |
|--------|-------------------------|
| 3      | 2                       |
| 4      | 6                       |
| 55     | 756                     |

Write the code below.

### Methods FRQ Part B
Write the sumComparison method which returns true if the return value of getEvenSum is greater than a randomly generated value. The randomly generated value must be divisible by 3 and 4 and be between 1 and max, inclusive. If the return value of getEvenSum is equal to or less than the randomly generated value, return false.

Write the code below.


## Class FRQ
This question involves the implementation of the Company class which represents a single company’s cellphone phone availability and prices.

The Company class provides a constructor and the following methods:

* getTotalCost, which returns the cost of purchasing a cellphone after the monthly fees are paid.
* setPhones, which changes the stock of cellphones after a purchase
* getPhones, which returns the total stock of cellphones remaining.
* phoneRefund, which updates the stock and price of a phone after phones are refunded.

The following table contains a sample code execution sequence and the corresponding results.

| Statements and Expression               | Value Returned (blank if no value) | Comment                                                                                                                                                                                                                                      |
|-----------------------------------------|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Company c = new Company(50, 100, 6, 20) |                                    | The first parameter is the down payment of the phone, the second parameter is the monthly cost, the third parameter is the amount of months of payment, and the fourth parameter is the stock of phones. Assume all parameters are positive. |
| c.getTotalCost();                       | 650.00                             | The total cost is calculated by adding the phone’s down payment to the total monthly costs.                                                                                                                                                  |
| c.setPhones(2);                         |                                    | The amount of phones increases by 2.                                                                                                                                                                                                         |
| c.getPhones();                          | 102                                | The amount of phones remaining is returned.                                                                                                                                                                                                  |
| c.setPhones(-5);                        |                                    | The amount of phones decreases by 5.                                                                                                                                                                                                         |
| c.getPhones();                          | 97                                 | The amount of phones remaining is returned.                                                                                                                                                                                                  |
| c.phoneRefund(6);                       | 103                                | The amount of phones remaining is returned and the down payment for a phone increases by 10 * amount of phones refunded, if more than 5 phones are refunded. In this case, the down payment would increase to $110.                          |
| c.phoneRefund(1);                       | 104                                | The amount of phones remaining is returned and the down payment stays the same because less than 5 phones are refunded.                                                                                                                      |
| c.phoneRefund(5);                       | 109                                | The amount of phones remaining is returned and the down payment stays the same because 5 or less phones are refunded.                                                                                                                        |


Write the complete Company class, including the constructor and any required instance variables and methods. Your implementation must meet all specifications and conform to the example.
