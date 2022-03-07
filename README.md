# makechnage-dp-vs-dc

## Dynamic Programming (DP)
Dynamic Programming (DP) is an algorithmic technique for solving an optimization problem by breaking it down into simpler subproblems and utilizing the fact that the optimal solution to the overall problem depends upon the optimal solution to its subproblems.

## Divide & Concur (DC)
An algorithm design paradigm. A divide-and-conquer algorithm recursively breaks down a problem into two or more sub-problems of the same or related type, until these become simple enough to be solved

## ./mkChange.py
Python file containg following solutions

### mkChangeDP
Make Change Solution leveraging Dynamic Programming

### mkChangeDC
Make Change Solution Leveraging Divde & Concur

## ./ipynb
Can be used to check out the run time of the implmented solutions. A good baseline compare for DC vs DP

## ./coins.txt
contains the coins you want to make the change with. Mine is using [1,5,10,25] for this example

## To Run
```
mkChange.py 1000 coins.txt
mkChangeDC
amount: 1000 coins: [1, 5, 10, 25] ways: 142511 calls: 0
mkChangeDP
amount: 1000 coins: [1, 5, 10, 25] ways: 142511 reads: 0
```