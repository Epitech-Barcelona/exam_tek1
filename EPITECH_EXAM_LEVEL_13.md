#EPITECH EXAM LEVEL 13

# REPOSITORY_NAME: epitech_machine_13_2019
# RIGHTS read:
  - mackendy-pierre.anselin@epitech.eu
  - edouard.loustau@epitech.eu
  - maxime.jenny@epitech.eu

|**RULES**|
|:--------|
| - NO INTERNET FOR THE SECOND PART (WIFI YES)
| - NO QUESTION
| - CAN'T TALK
| - ONLY DOCKER SESSION
| - PHONE SHUT DOWN ON THE TABLE
| - DO EXERCISES BY ORDER
| - ONLY WRITE, OPEN, CLOSE, GETLINE, MALLOC AND FREE AS SYSTEM FUNCTION ALLOW
| - NO SCRIPT (CREATE MY REPOSITORY NEITHER)

________________________________________________________________________________________

|**MANDATORY**|
|:-------------|
|(_You will get zero if it is not respected_)
|
| - Folder for each exercise **(ex: ex_01)**
| - Folder **include** with **".h"** files for each program  
| - Folder **src** with **".c"** files, for each program 


|**PROHIBITION**|
|:-----------:|
|(_You can get zero if it is not respected_)
|
| - NO SEGFAULT
| - No warning (it will be tested with error flags)
| - No Prototype function in ".c"
| - No More than one function by file
| - No question 
| - No Big code in the main

|**EXPECTED**|
|:-----------|
|(_You can lose points or get zero if it is not respected_)
|
| - Makefile with **make**, **make re**, **make clean**, **make fclean** for each program 
| - Main with arguments for each program
| - Main Return 84 to error 
| - Main Return 0 to success 

|**BE CAREFUL**|
|:-----------|
|(_You can lose points if it is not respected_)
|
| - Header (description, title)
| - Error handing
| - Read perfectly the subject
| - Your time
| - Don't make noise
| - Difference between **"write a function"** and **"write a program"**
| - To write a big code in the main

__________________________________________________________________________________________________________________________________________________________________________________


##PART 2

More exercises you will *TRY* more points you can get even if the exercise is not perfect.

Read the rules perfectly before starting and avoid losing points foolishly.

Be careful to the goal of the function or program.

Take 5 min to check everything is going to be ok before pushing.




####Exercise 1)

|my_swap_int|
|:----|
|Write a function which swaps the pointers of two int variable
|
|FOLDER     :   ex_01
|BINARY NAME:
|
|NAME       :   my_swap_int
|PARAMETER  :   number, number
|RETURN     :   





####Exercise 2)

|my_get_file_content|
|:----|
|Write a function which puts file content in array of int of int and returns the array
|All file content must be numbers otherwise the function return NULL
|You are not allowed to use hard malloc, 
|Your Allow to use getline system function 
|FOLDER     :   ex_02
|BINARY NAME:
|
|NAME       :   my_get_file_content
|PARAMETER  :   string
|RETURN     :   array





####Exercise 3)

|my_sort_print_comparator|
|:----|
|Write a program which prints **<** if the next argument it's superior to the left argument  
|Display **>**, if it's inferior, **==** if it's equal. 
|----------------------
|example :
|./ex_02 8 3 2 6 6 7 
|8 > 3 > 2 < 6 == 6 < 7  
|----------------------
|FOLDER     :   ex_03
|BINARY NAME:
|
|NAME       :   my_sort_print_comparator
|PARAMETER  :   
|RETURN     :   





####Exercise 4)

|my_sort_number_arg|
|:----|
|Write a program which sorts the arguments by ascending order
|The program will show the result
|----------------------
|example :
|./ex_02 8 3 2 6 7 
|2 < 3 < 6 < 7 < 8  
|----------------------
|FOLDER     :   ex_04
|BINARY NAME:
|
|NAME       :   my_sort_number_arg
|PARAMETER  :   
|RETURN     :   




####Exercise 5)

|my_sort_file_number|
|:----|
|Write a program which sorts the number in file by ascending order
|The program will display every action to sort the content
|All file contents should be numbers else the program doesn't work
|The actions :  swap --> swap with one gap
|               pop_end -> put the number at the beginning 
|               pop_beginning --> th number at the end 
|----------------------
|example : 
|cat file
|3 2 34 6 1
|
|./exo5 file
|swap swap_end swap swap_beginning
|
|example : 
|cat file
|3 2 a 6 1
|
|./exo5 file
|Error : all file content must be a number 
|----------------------
| 
|FOLDER     :   ex_05
|BINARY NAME:
|
|NAME       :   my_sort_file_number
|PARAMETER  :   
|RETURN     :   




####Exercise 6)

|my_sort_number_game|
|:----|
|Write a program which gets the file content
|The program will run the output commands  
|The command :  swap_left --> swap the number with number to the left 
|               swap_right --> swap the number with number  to the right
|               pop_end -> put the number at the end of the list  
|               pop_beginning --> put the number at the beginning of the list
|               number_left --> change the position of the player (go to the left number)   
|               number_right --> change the position of the player (go to the right number)   
|               first_number --> change the position of the player (go to the first number)   
|               last_number --> change the position of the player (go to the last number)   
|----------------------
|example : 
|cat file
|3 2 34 6 1
|
|./exo6 file
|3 > 2 < 34 > 6 < 1
|player position (3)  
|your command > swap_right
|
|2 < 3 < 34 > 6 < 1
|player position (2)   
|your command > right
|
|2 < 3 < 34 > 6 < 1
|player position (3)   
|your command > right
|
|2 < 3 < 34 > 6 > 1
|position (34)   
|your command > pop_end
|
|
|2 < 3 < 6 > 1 < 34
|position (6)   
|your command > swap_right
|
|
|2 < 3 > 1 > 6 < 34
|position (1)   
|your command > pop_beginning
|
|1 < 2 < 3 < 6 < 34
|position (1)   
|Well done !! You have sorted all number by ascending order, in (6) movements   
|
|./exo5 file
|Error : all file content must be numbers 
|----------------------
| 
|FOLDER     :   ex_05
|BINARY NAME:
|
|NAME       :   my_sort_number_game
|PARAMETER  :   
|RETURN     :   



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