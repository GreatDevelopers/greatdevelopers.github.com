---
layout: post
title:  "GNU Debugger"
date:   2016-06-29 11:32:00 +0530
author: "Amisha Budhiraja"
categories: presentation
---

Date-29.06.2016



**Amarjeet** Gave everybody a file with a bug to find the source of that bug and the error given by it was segmentation fault
then gave one by one tool that can be used to find the bug.

1. Guess

2. print/return

3. code review

4. assert statement

5. code walkthrough

and finally the debugger


gnu debugger

C/C++

break points.

**What was the error?**

segmentation fault but we did not know wheere this error was. So we used the backtrace option

Normal compilation: + g option is how we use this option.

How to open gdb:

gdb run program_name

Factorial File: 

a small file. We'll see all options on this file.

Break:

break filename line_no.

or

break filename function_name

Then you can run again,

And the program would run as normal but this time the program will stop at the break point and will also tell us the next statement to be executed is prnted.

To continue further, do the following command:
step,

and then the next statement would run.

And then from here in out, the program will run step by step i.e. statement by statement.

To see the values of various variable use the following commmand:

print

and the values will be stored in a special variable with a dollar sign. We can use this variable to change and access the values of these variables.


Enter quit to quit.

Next also does the same job as step but in next treates even function calls as one single statememt. But next goes inside the function as well.

Watch:

It will monitor the value of a particular variable. and will stop the execution when the value of that variable will change.

List:

Will return the rest of the program that is yet to run.

Info:

**Local**:This will return the information of all variables with current scope at the point of execution. 

**Register**: will show the value of all the cpu register.

**Stack**: will show what is going on in the stack.

**What about heap?**

Maybe.

Running the program.

Each time a statement is run, proper indentation of the running statement is also given by gdb, which is nice.

Disable:

This will disable a break point.

We can even do recompilation inside gdb during the debugging statement.

We can use this inside a make file as well.

Continue:

will run code between two break points without any stopage.

And there are many many other options that the presenter (Amarjeet) did not as of this presentation, explore.

**Question?**

Amisha: What is make?

Amarjeet: Used to compile big things.

Jugraj: All compilation in one place.

Amarjeet: I promise another presentation on Make.

Jugraj,Govind: Oh noooooo.

Some sincere discusion about make command. Amarjeet took it to heart and explained very well.

He refused show the make file as that was something he wanted to do in the next presentation.
