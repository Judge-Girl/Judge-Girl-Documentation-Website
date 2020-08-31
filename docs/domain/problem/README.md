# Problem

> Students are here to solve Problems!

Problem is the **most complicated and valuable entity** in Judge Girl. 
Problem must be designed to contain enough information to let Judge Girl know how to work. 
Problem contains a list of **[Test Cases](domain/problem/testcase/)** and some code-related stuff
such as **[Compilation Script](domain/problem/compilation-script/)**, 
**[Provided Codes](domain/problem/provided-code/)**, 
**[Env Spec](domain/problem/env-spec/)** and 
**[Submitted Code Specs](domain/problem/submitted-code-spec/)** 
so that Judge Girl knows what and how to compile and where to run the submitted code.

Student reads the Problem's description and Test Cases 
to understand what to solve and what codes to write.

Example Problem: Add two numbers
---

Attribute | Value |
------ | ------ | 
Id |  1
Title | Add two numbers
Tags | `C`, `Easy` |

Example Problem Description
---

**Task Description**

Write a program to read two integers a and b, then print their sum.

**Input Format**

There are two lines in the input. 
The first line has the integer a, the second line has the integer b.

**Output Format**

There is one lines in the output. The line has the sum of a and b.

**Sample Input**

> 2
> 3

**Sample Output**

> 5
