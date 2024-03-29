#EPITECH EXAM LEVEL 12

# REPOSITORY_NAME: epitech_machine_12_2019
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
| - ONLY WRITE, STAT, OPEN, CLOSE, GETLINE, MALLOC AND FREE AS SYSTEM FUNCTION ALLOW
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

________________________________________________________________________________________


##PART 1

More exercises you will *TRY* more points you can get even if the exercise is not perfect.

Read the rules perfectly before starting and avoid losing points foolishly.

Be careful to the goal of the function or program.

Take 5 min to check everything is going to be ok before pushing.




####Exercise 1)

|my_display_file_content|
|:----|
|Write a function which displays the content of the file
|FOLDER     :   ex_01
|BINARY NAME:   
|
|NAME       :   my_display_file_content
|PARAMETER  :   string
|RETURN     :




####Exercise 2)

|my_get_file_content|
|:----|
|Write a function which puts file content in array of string and returns the array
|Your Allow to use getline system function 
|Check man stat
|FOLDER     :   ex_02
|BINARY NAME:
|
|NAME       :   my_get_file_content
|PARAMETER  :   string
|RETURN     :   array





####Exercise 3)

|my_square_or_rectangle_map|
|:----|
|Write a program which tells if the map passing as argument is square or rectangle
|If it is not rectangle or square the program return 84 and ask the user to use the program with rectangular map or square map  
|
|----------------------
|example : 
|cat map
|XXXXXXXXXXXXXX
|X            X
|X            X
|X            X
|XXXXXXXXXXXXXX
|
|./exo3 map
|The map is rectangular shape of size (length) 14 by (width) 5
|
|_______________________________________________________________
|
|cat map
|XXXXXXXXXXXXXX
|X            X
|X            X
|X            X
|X            X
|X            X
|X            X
|X            X
|X            X
|X            X
|X            X
|X            X
|X            X
|XXXXXXXXXXXXXX
|
|./exo3 map
|The map is square shape of size 14 (length)  by 14 (width)
|
|_______________________________________________________________
|
|cat map
|X
|X X
|X   X
|X     X
|X       X
|X         X
|XXXXXXXXXXXX
|
|./exo3 map
|ex04 Error : the map must be a square shape or rectangle shape 
|
|----------------------
|FOLDER     :   ex_03
|BINARY NAME:   ex_03
|
|NAME       :   my_square_or_rectangle_map
|PARAMETER  :   
|RETURN     :  



####Exercise 4)

|my_analyse_personages_map|
|:----|
|Write a program which displays the number of players (**p**) and enemies (**e**) there are in the map
|The walls of the map must be a rectangle of uppercase x
|If there are players or un enemies out of the map, it is not good
|The bosses enemies is the uppercase e
|The bosses enemies is counted as a enemy
|
|----------------------
|example : 
|cat map
|XXXXXXXXXXXXXX
|X p          X
|X      e e E X
|X  p    e    X
|XXXXXXXXXXXXXX
|
|./exo4 map
|The map is rectangular shape of size (length) 14 by (width) 5 with 6 personages ((2 players), (4 enemies (1 Boss)))
|______________________________________________________
|
|cat map
|XXXXXXXXXXXXXX
|X p          X E
|X      E     X
|X  p    E    X
|XXXXXXXXXXXXXX
|
|./exo4 map
|the map is not good, there is (1) enemy out of the map
|
|cat map
|XXXXXXXXXXXXXX
|X p      E           X 
|X      E          X
|X  p    E    X
|XXXXXXXXXXXXXX
|
|./exo4 map
|the map is not good, it is not a square of uppercase x
|
|
|cat map
|XXXXXXXxXXXXXX
|X p      E   X     
|X      E     X
|X  p    E    X
|XXXxXxXXXXXXXX
|
|./exo4 map
|the map is not good, it is not a square of uppercase x
|----------------------
|FOLDER     :   ex_04
|BINARY NAME:   ex_04
|
|NAME       :   my_analyse_personages_map
|PARAMETER  :   
|RETURN     :  





####Exercise 5)

|my_analyse_map|
|:----|
|Write a program which does the same thing than exercise 4 but will take one argument more
|This argument will tell you what you have to display more  
|**--all-information** --> display all information about the map (positions of each personages) (the size of the my (length, width))
|**--players-information** --> only the position of each players (x, y)
|**--enemies-information** --> only the position of each enemies  (x, y)
|**--size-map-information** --> only the size of the map
|**--help** or **-h** --> show how to use the program
|Give a number for each player (p1, p2..) same with the enemies (e1, e2..) (Boss1, Boss2..) 
|----------------------
|example : 
|cat map
|XXXXXXXXXXXXXX
|X p          X
|X      e e E X
|X  p    e    X
|XXXXXXXXXXXXXX
|
|./exo5 map --all-information
|The map is rectangular shape of size (length) 14 by (width) 5 with 6 personages ((2 players), (4 enemies (1 Boss)))
|
|(2) players,
|p1 (3, 2) 
|p2 (4, 4) 
|
|(4) enemies
|Boss1 (12, 3)
|e1   (8,3)
|e2   (10, 3)
|e3   (9, 4)
|
|________________________________________________
|
|cat map
|XXXXXXXXXXXXXX
|X p   p      X
|X p    e     X
|X  E    e    X
|XXXXXXXXXXXXXX
|
|./exo5 map --players-information
|
|(3) players,
|p1 (3, 2) 
|p2 (7, 2) 
|p2 (3, 3) 
|
|
|./exo5 --help
|How to use : ./exo5 [MAP] [OPTION]..
|display the information about the map
|
|options:
|           --all-information   display all information about the map  (the size of the map (length, width)) (number of personages and also their positions)
|           --players-information   display all information about players (player number and position (x, y))
|           --enemies-information   display all information about enemies (enemies number and position (x, y))
|           --size-map-information   display all information about the size of the map (length, width)))
|__________________________________________
|----------------------
|FOLDER     :   ex_05
|BINARY NAME:   ex_05
|
|NAME       :   my_analyse_map
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
