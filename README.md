# 1. Boyer–Moore Majority Voting Algorithm
   Purpose:
   ---
   To find out Majority element in O(n) time and O(1) space
   
   Description:
   ---
    - We will sweep down the sequence starting at the pointer position 0.
    - As we sweep we maintain a pair consisting of a current candidate and a counter. Initially, the current candidate is unknown and the counter is 0.
      When we move the pointer forward over an element e:
      -- If the counter is 0, we set the current candidate to e and we set the counter to 1.
      -- If the counter is not 0, we increment or decrement the counter according to whether e is the current candidate.
    - When we are done, the current candidate is the majority element, if there is a majority.
   Link:
   ---
    http://www.cs.utexas.edu/~moore/best-ideas/mjrty/example.html
   Problem:
   ---
    https://leetcode.com/problems/majority-element/
   

