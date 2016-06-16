---
layout: post
title:  "Coding Conventions"
date:   2016-06-09 11:32:00 +0530
author: "Amisha Budhiraja"
categories: presentation
---

﻿Date-09.06.2016


**Coding Conventions(Amarjeet)**

Coding conventions are a set of guidelines for a specific programming language
that recommend programming style, practices and methods for each aspect of a
piece program written in this language.

**Coding standards**

Where coding conventions have been specifically designed to produce high-quality
 code, and have then been formally adopted, they then become coding standards.

**Coding conventions**
  
  - Comment conventions
  
  - Indent style conventions
  
  - Line length conventions
  
  - Naming conventions
  
  - Programming style conventions

**Commenting**

    Due to time restrictions or enthusiastic programmers who want immediate
    results for their code, commenting of code often takes a back seat.
    Programmers working as a team have found it better to leave comments behind
     since coding usually follows cycles, or more than one person may work on a
    particular module. However, some commenting can decrease the cost of
    knowledge transfer between developers working on the same module.
    
    In the early days of computing, one commenting practice was to leave a brief
     description of the following:

      -  Name of the module.
      
      -  Purpose of the Module.
      
      -  Description of the Module (In brief).
      
      -  Original Author
      
      -  Modifications
      
      - Authors who modified code with a description on why it was modified.

Programs written only for the machine have two
problems:
    
    They are difficult to correct because sometimes even the
    author does not understand them.
    
    Modifications and upgrades are difficult to make because the
    maintenance programmer must spend a considerable
    amount of time figuring out what the program does from its
    code    
    


/*
     This is the comment body.
     Variation One.
*/

/***************************\
*                           *
* This is the comment body. *
* Variation Two.            *
*                           *
\***************************\



 /* This is the style recommended by Holub for C and C++.
  * It is demonstrated in ''Enough Rope'', in rule 29.
  */

 /* This is another way to do it, also in C.
 ** It is easier to do in editors that do not automatically indent the second
 ** through last lines of the comment one space from the first.
 ** It is also used in Holub's book, in rule 31.
 */

**Tags:-**

    FIXME - should be corrected.
    HACK - a workaround.
    TODO - something to be done.
    UNDONE - a reversal or "roll back" of previous code.
    XXX - warn other programmers of problematic or misguiding code
    UX - user experience, notice about non-trivial code.


**Naming conventions**

    Use of proper naming conventions is considered good practice. Sometimes
    programmers tend to use X1, Y1, etc. as variables and forget to replace them
     with meaningful ones, causing confusion.

    In order to prevent this waste of time, it is usually considered good
    practice to use descriptive names in the code since we deal with real data.
    Example: A variable for taking in weight as a parameter for a truck can be
    named TrkWeight or TruckWeightKilograms, with TruckWeightKilograms being the more
    preferable one, since it is instantly recognisable.
    

**Indent style**

    Placement of braces
    
        if (total <= 0) {
            std::cout << "You owe nothing\n";
            total = 0;
        } else {
            std::cout << "You owe " << total << " dollars\n";
            all_totals = all_totals + total;
        }
        
        In this case, most of the curly braces are put on the same line
        as the statements. The other style puts the curly braces on
        lines by themselves:
        
            while (! done)
            {
                std::cout << "Processing\n";
                next_entry( );
            }
    Tabs, spaces, and size of indent
    
**Characters per line**
  
    80
  
    100
  
    120
  
    180


The first 90 percent of the code accounts for the first 10 percent of the
development time. The remaining 10 percent of the code accounts for the other 90
 percent of the development time.

1. Various ways to write comments like inline

VArious tags like Fixme, XXX, HACK etc

What is the meaning of XX tag?

2. Variable name should be meaningful.
Define variables locally also.
Avoid global variables.

3. Use indentations because it maintain consistency and looks beautiful.

Different ways are there to put brackets.

If we start bracket  after for loop directly in the same line, it is closed method.

What is the name of the method in which bracket came in next line?


4. Characters per line

72

79

80

100

120

THe first 90% of the code accounts for the first 90 percent of the development time. The remaining 10 percent of the code accounts for the other 90 percent of the development time.

Division of program and functions is a good practice of programming. 

Function defined inside the class is by default inline function.

Commenting on function which is declared in class and defined outside.
