# Running-Time-of-Algorithms
Can you modify your previous Insertion Sort implementation to keep track of the number of shifts it makes while sorting? The only thing you should print is the number of shifts made by the algorithm to completely sort the array. A shift occurs when an element's position changes in the array. Do not shift an element if it is not necessary.

Function Description

Complete the runningTime function in the editor below. It should return an integer representing the number of shifts it will take to sort the given array.

runningTime has the following parameter(s):

arr: an array of integers

Sample Input

5
2 1 3 1 2
Sample Output

4
Explanation

Iteration   Array      Shifts
0           2 1 3 1 2
1           1 2 3 1 2     1
2           1 2 3 1 2     0
3           1 1 2 3 2     2
4           1 1 2 2 3     1

Total                     4

HackerRank: https://www.hackerrank.com/challenges/runningtime/problem
