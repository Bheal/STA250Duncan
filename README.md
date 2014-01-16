STA250Duncan
============

================================
==== HW Due 1/16 Description ===
================================

Assignments for STA250 course by Duncan Temple Lang. In this part of assignment 1, I have found the mean, median and standard deviation of the ArrDelay values from 1987 to 2007. The following methods have been implemented.

1. Extract ArrDelay field using R for each year and subsequently updating certain statistics.
2. Extract ArrDelay field using Shell for each year and subsequently updating certain statistics.

As an updation method, a modified version of Welford's formula have been applied. This can be found in the "formula.pdf" file. The R codes "code1" and "code2" implement method 1 and 2 respectively. In order to calculate median, a frequency table of ArrDelay values is formed and modified at each iteration. 

"result1.RData" and "result2.RData" has all the results in the required format.
