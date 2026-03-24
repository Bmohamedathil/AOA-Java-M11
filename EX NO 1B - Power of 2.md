Skip to content
Sudhakaran2452
AOA-Java-M11
Repository navigation
Code
Pull requests
Actions
Projects
Security
Insights
You’re making changes in a project you don’t have write access to. Submitting a change will write it to a new branch in your fork Bmohamedathil/AOA-Java-M11, so you can send a pull request.
AOA-Java-M11
/
EX NO 1B - Power of 2.md
in
main

Edit

Preview
Indent mode

Spaces
Indent size

2
Line wrap mode

Soft wrap
Editing EX NO 1B - Power of 2.md file contents
  1
  2
  3
  4
  5
  6
  7
  8
  9
 10
 11
 12
 13
 14
 15
 16
 17
 18
 19
 20
 21
 22
 23
 24
 25

# EX 1B Power of 2

## AIM:
To write a Java program to for given constraints.Given an integer n, return true if it is a power of two. Otherwise, return false.

An integer n is a power of two, if there exists an integer x such that n == 2x.

## Algorithm
1. Start  
2. Read an integer `n` from the user.  
3. Check if `n` is greater than 0 **and** the number of 1's in its binary representation is exactly 1 using `Integer.bitCount(n) == 1`.  
4. If both conditions are true, return `true` — meaning `n` is a power of two. Otherwise, return `false`.  
5. Print the result and end.  
   

## Program:
```


import java.util.*;

public class Solution {

    public boolean isPowerOfTwo(int n) {
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
