---

layout: post
title:  "libdxfrw library"
date:   2016-07-05 8:00:00 +0530
author: "Gagandeep kaur"
categories: presentation

---
﻿Date-05.07.2016

##libdxfrw library: c++ library (read/write dxf drawing)

**It is used to make:**
line
point
text


**library structure:**
	1. entitywriter.cpp (function define)
	2. entitywriter.h (functions declaring)
	3. main.cpp (execute input.cpp file of user)
	4. input.cpp (user end file)	


**entitywriter.h**
	there are all the functions inside it
	like function of line,circle.
	declaring variable in input.cpp files

using loops in input.cpp files (everything in c++).
parameteric input by variables declaring above.

**entities** 	
	point 
	text
	arc
	trace
	dimensions - not working at present
	wall
	

**Discussion of layer:**
	
**To do:**
	run program through cgi. User can give the input in the form as webpage by CGI.


**Question asked by saini:**
	*sir reply:* arc everytimes is circular but not parabolic. (i.e. spline)

Sir suggested use this library unstead Autocad (to civil student): because it take time to start.

**Asked question by Monisha :**
What would be the arguments of the dimension :
	Sir replied, first give dimension on graph paper manually.
Or
Dimensioning:
	two point pass in dimensions: (starting point, ending point)
	
