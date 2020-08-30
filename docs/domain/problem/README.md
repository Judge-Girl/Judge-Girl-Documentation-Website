# Problem

Problem is the **most complicated Entity** in Judge Girl as 
it's the most valuable content the Judge Girl's admin must provide.

Problem contains a list of [Test Cases](domain/problem/testcase/) and some code-related stuff
such as [Compilation Script](domain/problem/compilation-script/), [Provided Codes](domain/problem/provided-code/), 
and [Submitted Code Specs](domain/problem/submitted-code-spec/) so that Judge Girl knows how to compile
the submitted codes for a problem.


🚧 TODO 🚧

Specs
---

Attribute | Type | Description
------ | ------ | ------ |
 Id | number |  the sequential id of the problem. |
Title | text (length=1..100) | the title of the problem
Description | text, markdown |  the detailed description of the problem in a form of markdown
Tags | text [0..*] | a set of tags the problem is attached |
Compilation Script | text, code |  the code (typically [shell script](https://en.wikipedia.org/wiki/Shell_script)) that compiles the submitted codes with the provided codes. |
Submitted Code Specs | [Submitted Code Spec](domain/problem/submitted-code-spec/) [*] | a list of Submitted Code Specs |
Provided Codes | [Provided Code](domain/problem/provided-code/) [*] | a list of Provided Codes|
 

> For the further requirements, every problem may also present the following:
> - How many submissions have been made to the problem (number)
> - The AC-Error ratio 


---

Example: Add two numbers
---

Attribute | Value |
------ | ------ | 
Id |  123
Title | Add two numbers
Description |  Given two numbers, can you add them together and show the result? |
Tags | `C`, `Easy` |
Compilation Script | `gcc -l add.h -l main.h add.c` |
