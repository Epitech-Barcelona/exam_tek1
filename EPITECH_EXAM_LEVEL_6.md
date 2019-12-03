#EPITECH EXAM LEVEL 4

# REPOSITORY_NAME: epitech_machine_4_2019
# RIGHTS read:
  - mackendy-pierre.anselin@epitech.eu
  - edouard.loustau@epitech.eu
  - maxime.jenny@epitech.eu

|**RULES**|
|:--------|
| - NO INTERNET FOR THE SECOND PART (WIFI YES)
| - NO QUESTIONS
| - CAN'T TALK
| - ONLY DOCKER SESSION ALLOWED
| - PHONE HAS TO BE SHUT DOWN ON THE TABLE
| - DO EXERCISES BY ORDER
| - ONLY WRITE, MALLOC AND FREE SYSTEM FUNCTION ALLOW
| - NO SCRIPTS (CREATE MY REPOSITORY NEITHER)

________________________________________________________________________________________

|**MANDATORY**|
|:-------------|
|(_You will get zero if ONE OF THEM are not respected_)
|
| - Folder for each exercise **(ex: ex_01)**
| - Folder **include** with **".h"** files for each program  
| - Folder **src** with **".c"** files, for each program 


|**PROHIBITION**|
|:-----------:|
|(_You can get zero if ONE OF THEM are not respected_)
|
| - NO SEGFAULT
| - No warning (it will be tested with error flags)
| - No Prototype function in ".c"
| - No More than one function by file
| - No questions
| - Don't code all yours programs into the main function !

|**EXPECTED**|
|:-----------|
|(_You can loose points or get zero if ONE OF THEM are not respected_)
|
| - Makefile with **make**, **make re**, **make clean**, **make fclean** for each program 
| - Main with arguments for each program
| - Main Return 84 to error 
| - Main Return 0 to success 

|**BE CAREFUL**|
|:-----------|
|(_You can loose points if ONE OF THEM are not respected_)
|
| - Header (description, title)
| - Error handing
| - Read perfectly the subject
| - Manage your time
| - Don't make noise
| - Difference between **"write a function"** and **"write a program"**
| - Avoid writing all your code into the main function

________________________________________________________________________________________

##PART 1

More exercises you [do / try] can give you more points even if the exercise is not perfect.

Read the rules perfectly before starting and avoid losing points foolishly.

Be careful to the goal of the function or program.

Take 5 min to check everything is going to be ok before pushing.


####Exercise 0)

FUNCTION NAME: none
DESCRIPTION: You MUST define a structure named my_struct that containing: - an integer - a string.
This variable's name don't matter.. But the name of the struct is important, think Coding Style !
By the way, maybe a typedef could be useful for later..

FOLDER     :   ex_00

FILENAME   :   my_struct.h   
PARAMETER  :   none
RETURN     :   none


####Exercise 1)

FUNCTION NAME: display_z
DESCRIPTION: Write a function which display the character 'z' followed by a new line.

FOLDER     :   ex_01
BINARY NAME:	ex_01

NAME       :   display_z
PARAMETER  :   none
RETURN     :   none

####Exercise 2)

FUNCTION NAME: my_insensitive_check
DESCRIPTION: Write a function which compare these 2 arguments on case insensitive way.
Returns true if perfect match, or false.

FOLDER     :   ex_02
BINARY NAME:   ex_02

NAME       :   my_custom_print_revalpha
PARAMETER  :   String, String
RETURN     :   Boolean

Expected output: zYxWvUtSrQpOnMlKjIhGfEdCbA

####Exercise 3)

FUNCTION NAME: my_crazy_loop
DESCRIPTION: Write a program which display all numbers between the range passed as parameters.

FOLDER     :   ex_03
BINARY NAME:   ex_03

NAME       :	my_crazy_loop
PARAMETER  :	Int, Int
RETURN     :	none

Expected output with my_crazy_loop(10, 20) => 10, 11, 12, 13, 14, 15, ... 18 ,19
Expected output with my_crazy_loop(20, 10) => 20, 19, 18, 17, 16, 15, ... 12, 11

####Exercise 4)

FUNCTION NAME: my_lovely_struct_filled
DESCRIPTION: Write a function which takes 2 parameters. The first value is the number total of arguments received on the execution. The second one is all the arguments received on the execution. You MUST set the Integer from the structure to the number total of argument (Binary name not included). Then, you MUST set the string to contain each last character of each arguments. Finally, return your lovely structure..

FOLDER     :   ex_04
BINARY NAME:	ex_04

NAME       :   my_lovely_struct_filled
PARAMETER  :   Array of String
RETURN     :   t_my_struct

Example:
	./ex_04 Hola "Que Tal" 33 Pulpo
	the string on the struct has to contain "al3o" and the integer set to 4 in this case.

####Exercise 5)

FUNCTION NAME: my_lovely_linked_list
DESCRIPTION: You kinda love structure right now, let's flirt now with the linked list. The goal is pretty simple. You have to build a linked list with all arguments passed during the execution.
A simple linked list should be great for today ! Adapt your actual structure created since the beginning that fit well with what you need to do !

FOLDER     :   ex_05
BINARY NAME:   ex_05

NAME       :   my_lovely_linked_list
PARAMETER  :   Char **
RETURN     :   t_my_struct

__________________________________________________________________________________________________________________________________________________________________________________


|**ADVISE**|
|:-------------|
|(_ARE YOU SURE ALL IS PERFECTLY WELL DONE ??_)
|
| - Did you test all exercise you did ?
| - Does your code is clean ?  
| - Did you give good right?  
| - Did you try to compile ?
| - Did you respect all rule ?
| - Did you resolve all your segfault ?
| - Did you push ?
| The most important did you learn something ?

If you sure all is perfectly so you can tell the supervisor.
 
**>> Watch out if you are making noise during your classmates manage to their exam you get zero directly!!<<** 
