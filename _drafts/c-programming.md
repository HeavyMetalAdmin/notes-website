---
date:
title:
categories:
description:
type: Document
---

**\# C++ Programming**

**\#\# Structure**

\-&nbsp;**\*\*//\*\***&nbsp;= comment

\- '**\*\*\#\*\***' =&nbsp;directives, instructs compiler to include the code from the referenced library

\-&nbsp;**\*\*namespace\*\***&nbsp;= group a&nbsp;set of classes, functions, etc. under a&nbsp;name

\-&nbsp;**\*\*;\*\***&nbsp;= terminator, at the end of the command

\-&nbsp;**\*\*main\*\***&nbsp;= where the program execution starts, first code executed

\-&nbsp;**\*\*\{\}\*\***&nbsp;= contain the body of the function that they are nested under

\-&nbsp;**\*\*cout\*\***&nbsp;= standard output, prints to console

\-&nbsp;**\*\*return\*\***&nbsp;= can have different values and functions

**\#\# Variables & Types**

\- Variables are portions of the memory where values are stored

&nbsp; -&nbsp;Has a&nbsp;unique identifier or name

&nbsp; -&nbsp;Global variable

&nbsp; &nbsp; -&nbsp;Declared in the body of the source code

&nbsp; &nbsp; -&nbsp;Can be referred anywhere

&nbsp; -&nbsp;Local variable

&nbsp; &nbsp; -&nbsp;Declared inside the body of functions

&nbsp; &nbsp; -&nbsp;Can only be referred in THAT function

\- Small list of variables

&nbsp; -&nbsp;\!\[image-20200117080759318\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117080759318.png)

**\#\# Input /&nbsp;Output**

\-&nbsp;**\*\*cout\*\***&nbsp;is the standard output and prints to console

\-&nbsp;**\*\*&lt;&lt;\*\***&nbsp;tells the compiler to insert the next data into the stream

\-&nbsp;**\*\*endl\*\***&nbsp;= new line character, flushes the buffer

\-&nbsp;**\*\*cin\*\***&nbsp; is the standard input, takes user input into the stream

&nbsp; -&nbsp;Must be stored in a&nbsp;variable

\-&nbsp;**\*\*cin.ignore()\*\***&nbsp;is used to clean the buffer and keep the console opened

**\#\# Operators**

\-&nbsp;**\#\#\# 4&nbsp;Main Classes of Operators:**

&nbsp; -&nbsp;**\*\*Arithmetic\*\***

&nbsp; &nbsp; -&nbsp;\!\[image-20200117081847345\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117081847345.png)

&nbsp; &nbsp; -&nbsp;Increment operator&nbsp;**\*\*(++)\*\***&nbsp;= adds 1&nbsp;to its operand

&nbsp; &nbsp; &nbsp; -&nbsp;Can precede or follow an operand

&nbsp; &nbsp; &nbsp; &nbsp; -&nbsp;**\*\*(x++)\*\***

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -&nbsp;Operations preformed before obtaining the value of the operand

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -&nbsp;\!\[image-20200117082215943\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117082215943.png)

&nbsp; &nbsp; &nbsp; &nbsp; -&nbsp;**\*\*(++x)\*\***

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -&nbsp;Operations preformed after obtaining the value of the operand

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -&nbsp;\!\[image-20200117082232834\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117082232834.png)

&nbsp; &nbsp; -&nbsp;Increment operator\*\*(++)\*\* adds 1&nbsp;to its operand

&nbsp; &nbsp; -&nbsp;Decrement operator\*\*(--)\*\* subtracts 1&nbsp;from its operand

&nbsp; -&nbsp;**\*\*Relational\*\***

&nbsp; &nbsp; -&nbsp;Defines relationship between two values

&nbsp; &nbsp; -&nbsp;\!\[image-20200117082445015\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117082445015.png)

&nbsp; &nbsp; -&nbsp;Used to evaluate a&nbsp;comparison between two expressions, returns a&nbsp;Boolean value

&nbsp; &nbsp; &nbsp; -&nbsp;\!\[image-20200117083027537\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117083027537.png)

&nbsp; -&nbsp;**\*\*Logical\*\***

&nbsp; &nbsp; -&nbsp;Defines previous relationships must be connected

&nbsp; &nbsp; -&nbsp;\!\[image-20200117082531153\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117082531153.png)

&nbsp; &nbsp; -&nbsp;Any value other than zero is&nbsp;**\*\*TRUE\*\***

&nbsp; &nbsp; &nbsp; -&nbsp;1 for returned value

&nbsp; &nbsp; -&nbsp;Zero is&nbsp;**\*\*FALSE\*\***

&nbsp; &nbsp; &nbsp; -&nbsp;0 for returned value

&nbsp; &nbsp; -&nbsp;bool data type is used to express TRUE or FALSE statements, automatically converts 0&nbsp;to FALSE and 1&nbsp;to TRUE

&nbsp; &nbsp; -&nbsp;\!\[image-20200117083627296\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117083627296.png)

&nbsp; -&nbsp;**\*\*\! =\*\***&nbsp;only has one operand (right) and it inverses this value to determine if it's true or false

&nbsp; -&nbsp;**\*\*&& (AND)\*\***&nbsp;= &nbsp;evaluates two expressions to obtain the relational results

&nbsp; &nbsp; -&nbsp;**\*\*TRUE\*\***&nbsp;if both operands are&nbsp;**\*\*TRUE\*\***

&nbsp; &nbsp; -&nbsp;**\*\*FALSE\*\***&nbsp;if one operand is&nbsp;**\*\*FALSE\*\***

&nbsp; -&nbsp;**\*\*\|\| (OR)\*\***&nbsp;= evaluates two expressions to obtain the relational results

&nbsp; &nbsp; -&nbsp;**\*\*TRUE\*\***&nbsp;if either operand is&nbsp;**\*\*TRUE\*\***

&nbsp; &nbsp; -&nbsp;**\*\*FALSE\*\***&nbsp;if&nbsp;*\*BOTH\**&nbsp;are&nbsp;**\*\*FALSE\*\***

&nbsp; -&nbsp;**\*\*Bitwise\*\***

&nbsp; &nbsp; -&nbsp;Operations refer to testing, setting, or shifting the actual bits in the byte or word

&nbsp; &nbsp; -&nbsp;\!\[image-20200117085401013\](C:\\Users\\michael.padderatz\\Pictures\\image-20200117085401013.png)

\-&nbsp;**\*\*lvalue\*\***&nbsp;is ANY label that appears on the left of a&nbsp;assignment statement, variable name

\-&nbsp;**\*\*rvalue\*\***&nbsp;is ANYTHING to the right of a&nbsp;assignment statement, value assigned to the variable

**\#\# Iteration & Conditional Structures**

**\*\*Three main groups of statements:\*\***

**\*\*Selection\*\***

\-&nbsp;**\*\*if\*\***

&nbsp; -&nbsp;If the expression is evaluated to true the&nbsp;**\*\*IF\*\***&nbsp;expression is executed, otherwise the&nbsp;**\*\*ELSE\*\***&nbsp;expression is executed

&nbsp; -&nbsp;One or the other, both codes are never executed

&nbsp; -&nbsp;Can be nested statements

&nbsp; -&nbsp;\!\[image-20200120073300865\](C:\\Users\\michael.padderatz\\Pictures\\image-20200120073300865.png)

\-&nbsp;**\*\*switch\*\***

&nbsp; -&nbsp;Evaluates expression in order against a&nbsp;list of values

&nbsp; -&nbsp;Only the block of code that matches is executed

&nbsp; -&nbsp;**\*\*MUST\*\***&nbsp;be an integer or constant

&nbsp; -&nbsp;\!\[image-20200120073236051\](C:\\Users\\michael.padderatz\\Pictures\\image-20200120073236051.png)

&nbsp; -&nbsp;Value of the expression is tested against all case statements, when a&nbsp;match is found that block is executed until the break the statement

&nbsp; -&nbsp;If no value is matched the default statement is executed, if this is not put it in nothing happens

**\*\*Iteration\*\***

\-&nbsp;**\*\*while\*\***

&nbsp; -&nbsp;\!\[image-20200120074446347\](C:\\Users\\michael.padderatz\\Pictures\\image-20200120074446347.png)

&nbsp; -&nbsp;statement =&nbsp;can be empty, single, or a&nbsp;block of statements

&nbsp; -&nbsp;condition =&nbsp;can be any expression, and is true as long is any non-zero value is present

&nbsp; -&nbsp;loop continues while the condition evaluates to true

&nbsp; -&nbsp;when loop evaluates to false, the execution goes to the line of code after the loop

\-&nbsp;**\*\*for\*\***

&nbsp; -&nbsp;\!\[image-20200120073814667\](C:\\Users\\michael.padderatz\\Pictures\\image-20200120073814667.png)

&nbsp; -&nbsp;initialization =&nbsp;assignment statement that sets the starting value of the loop control variable

&nbsp; -&nbsp;condition =&nbsp;determines when the loop ends

&nbsp; -&nbsp;increment =&nbsp;determines how the control variable changes each iteration&nbsp;

&nbsp; -&nbsp;\!\[image-20200120074015950\](C:\\Users\\michael.padderatz\\Pictures\\image-20200120074015950.png)

&nbsp; &nbsp; -&nbsp;Starts with 2, goes until a&nbsp;=50, increases the control by 2

&nbsp; -&nbsp;Infinite loop created by for(;;), while stop for a&nbsp;break condition

\-&nbsp;**\*\*do-while\*\***

&nbsp; -&nbsp;\!\[image-20200120074717927\](C:\\Users\\michael.padderatz\\Pictures\\image-20200120074717927.png)

&nbsp; -&nbsp;loop checks are checked at the end of the loop

&nbsp; -&nbsp;executes at least once

**\*\*Jump\*\***

\-&nbsp;**\*\*break\*\***

&nbsp; -&nbsp;Can be used in loops and switch statements

&nbsp; -&nbsp;When encountered the execution jumps to the code following the switch statement

&nbsp; -&nbsp;used in conjunction with loop statements

&nbsp; -&nbsp;

\-&nbsp;**\*\*continue\*\***

&nbsp; -&nbsp;used in conjunction with loop statements

&nbsp; -&nbsp;forces code to continue to next iteration of a&nbsp;loop

\-&nbsp;**\*\*goto\*\***

&nbsp; -&nbsp;can make program unreadable

&nbsp; -&nbsp;requires a&nbsp;label

&nbsp; -&nbsp;label =&nbsp;identifier followed by a&nbsp;colon

&nbsp; &nbsp; -&nbsp;*\*label :\**&nbsp;

&nbsp; -&nbsp;cannot jump between functions

&nbsp; -&nbsp;must be in the same block of statements as the goto statement

\-&nbsp;**\*\*return\*\***

&nbsp; -&nbsp;used to return from function

&nbsp; -&nbsp;may or may not have value associated

&nbsp; -&nbsp;function stops executing when it encounters the first return

**\#\# Pointers**

\- variable that holds a&nbsp;memory address, this address is the location of another object in memory

\- must be written in a&nbsp;specific format

&nbsp; -&nbsp;type =&nbsp;base type of the pointer (int, char ...)

&nbsp; &nbsp; -&nbsp;defines the type of variable the pointer can point to

&nbsp; -&nbsp;name =&nbsp;name (identified) of the variable

\- \!\[image-20200120082513599\](C:\\Users\\michael.padderatz\\Pictures\\image-20200120082513599.png)

\- Special pointer operators:

&nbsp; -&nbsp;(\*) =&nbsp;returns the value located at the address

&nbsp; -&nbsp;& =&nbsp;returns the memory address of the variable

**\#\# \*\*Arrays\*\***

\- Collection of variables of the same type

\- Elements are access by an index

\- \!\[image-20200120083448074\](C:\\Users\\michael.padderatz\\Pictures\\image-20200120083448074.png)

\- type =&nbsp;declares the type of array

\- size =&nbsp;defines the length of the array

\- 0&nbsp;is the first element in the index