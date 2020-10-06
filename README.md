# 21-DAYS-PROGRAMMING-CHALLENGE-ACES
### CP is OP :heart:  Saying hi to DP! :fire::fire:
---
<br/>

# Dynamic Programming :rocket::rocket:

### Definition : :orange_book:
```
Simply cached Recusrion (Memoization) or in other words enhanced recursion.
```
##### _The main idea behind DP is to store the results of subproblems so that we can simply use results of these subproblems without re-computing them when needed in future. This idealogy saves a lot of time and make the solution optimized._
---
## Day - 1 :blue_book:
#### Knapsack Problem: :pushpin::pushpin:
_In this problem we are given an empty bag with its maximum weight holding capacity. Also we are given a list of items with there weight and profit values. We need to find out the maximum profit we can earn._
#### Type of Knapsack Problems
- ***Fractional Knapsack*** - It is simply a greedy problem. In this we can take fraction values. ***for eg. if we have space of 3 kg. left in a knapsack and we have an item of 6 kg that values 50 rs. , then we can take 50% of that item and we will gain profit of 25 rs.***

- ***0/1 Knapsack*** - It is a classical dp problem. Many biginner level problems are variation of this problem. In this we have only have two choices, either we include the item in Knapsack or we don't.

- ***Unbounded Knapsack*** - It is similar to 0/1 Knapsack but in this we can include same item multiple number of times.


```diff
! solved a classical knapsack problem using only recursion.
```
---

## Day - 2 :green_book:
### Memosisation :pushpin::pushpin:
_It is basically an **optimization technique** used to cache the results of subproblems so that we can use that results later on if required. **Memoization** ensures that a method doesn't run for the inputs whose results are previously calculated._

The dimensions of the memoisation array/table deepends upon variables.
If in recursive function:

- 1 variable is changing on recursive call, we will create a linear vector/array. ***E.g.  Fibonacci series***
- 2 variables are changing on recursive call, then we will use 2-D matrix to store results of sumproblems. ***E.g. Longest Common Subsequence***
- and so on.....for 3, 4..n variables.

#### _Generally we should initialise these matrices with -1 and later on we can check that if value of a particular cell is not  -1 then we will directly return that particular  cell value. else we will do a recursive call and set the cell value and finally return the cell value._

```diff
+ solved a classical knapsack problem using memoisation technique.
```
### Problem solved
|  Platform    | Title           |  Solution       | Difficulty    |
|--------------|---------------- | --------------- |---------------|
 GEEKSFORGEEKS |[0 - 1 Knapsack Problem](https://practice.geeksforgeeks.org/problems/0-1-knapsack-problem/0) | [View Solution](./DAY-2/0-1_Knapsack_Problem_(GEEKSFORGEEKS).cpp) | Easy |||
***
