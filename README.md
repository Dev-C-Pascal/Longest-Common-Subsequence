# __Fully solved LeetCode problem 1143__

## Longest Common Subsequence
Given two strings text1 and text2, return the length of their longest common subsequence. If there is no common subsequence, return 0.

A subsequence of a string is a new string generated from the original string with some characters (can be none) deleted without changing the relative order of the remaining characters.


# Complexity

__Time compexity -> O(n*m)__
 - each cell have constant time complexity, and we have to go through all cell's in matrix N x M.

__Memory compexity -> O(n*m)__
 -  we have to store all the values in each cell, requires, N x M memorry for our matrix.

## Example 1:

Input: text1 = "abcde", text2 = "ace" 
Output: 3  
Explanation: The longest common subsequence is "ace" and its length is 3.

<img width="956" alt="image" src="https://github.com/Dev-C-Pascal/Longest-Common-Subsequence/assets/80202137/d18fe51a-897b-492c-a3f5-739d95d5e3fd">

## Example 2:

Input: text1 = "abc", text2 = "abc"
Output: 3
Explanation: The longest common subsequence is "abc" and its length is 3.
<img width="955" alt="image" src="https://github.com/Dev-C-Pascal/Longest-Common-Subsequence/assets/80202137/78276105-0cbd-492e-a413-4119091fb2da">

## Example 3:

Input: text1 = "abc", text2 = "def"
Output: 0
Explanation: There is no such common subsequence, so the result is 0.

<img width="959" alt="image" src="https://github.com/Dev-C-Pascal/Longest-Common-Subsequence/assets/80202137/57eacdfe-af56-438f-8e14-1c653871b301">





 

