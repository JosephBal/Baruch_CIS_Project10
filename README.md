# Baruch_CIS_Project10
This was my 11th project in my CIS 2300 "Programming and Computational Thinking" led by professor Sadat Chowdhury

# Project Description

In the popular game called Scrabble, each letter of the English alphabet has a particular score as described in the table below: 

| Letter              | Score |
|---------------------|-------|
| A,E,I,O,U,N,R,T,L,S | 1     |
| D,G                 | 2     |
| B,C,M,P             | 3     |
| F,H,V,W,Y           | 4     |
| K                   | 5     |
| J,X                 | 8     |
| Q,Z                 | 10    |


The Scrabble score of a word is the sum of the scores of its letters.

Thus, the words 'ANT', 'QUIZ', and 'APPLE' are scored in the following way:

ANT = A+N+T = 1 + 1 + 1 = 3

QUIZ = Q+U+I+Z = 10 + 1 + 1 + 10 = 22

APPLE = A+P+P+L+E = 1 + 3 + 3 + 1 + 1 = 9

For this project you will be provided with a list of 500 common names in main.py

**Complete the Python program so that it prints the sum of Scrabble scores of all names from that list that has the following properties:**

**The names have at most two unique letters in common with your 7 letter unique word.**

As an example, if your word is ORCHIDS, then the name MARY matches this condition (because 1 unique letter -- R -- is common) and should be considered when computing the Scrabble score sum. Similarly, MARCY also matches (because two unique letters, R and C are common). The name JERRY also matches this condition (because R is uniquely common to both). However, the name PATRICIA does not match (R,I,C are 3 unique letters common with ORCHIDS).
