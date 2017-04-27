# bash_shell_proj

PROJECT TITLE:
---------------------------

Bash Shell Project - https://github.com/KevFan/bash_shell_proj


PURPOSE OF PROJECT:
------------------------------
The purpose of this project is apply concepts learned from the computer systems module to date to create a user friendly bash shell script based on an business scenario.

The business scenario involves being approached by an small local company, which requires a Linux- based software tool to allow them to track their business contact details.

A "menu driven" shell program is developed that will allow the user to interactively update (i.e. add, remove), search and list all their customer information, which is stored locally in a file called CustomerDetails.
The format of the " CustomerDetails " file should take the following format:
{E-mail Address}	{Alias}		{Address}		{Telephone}		{Number}


HOW TO START THIS PROJECT:
-------------------------------
To start the project, download/clone the repository and browse to directory using a terminal on a linux based system.

From the terminal, run the ./Menu to run the Menu script and which will bring you to the Menu of the project.


USER INSTRUCTIONS:
----------------------------------
The project has only been tested in the ubuntu terminal. After running the ./Menu script, you will be brought to the following menu :


Welcome. Please choose one of the following:

	1. Add a new Customer
	2. Remove an existing Customer
	3. Search for a Customer
	4. E-mail a Customer

Enter a Number:


From this menu, the user and enter the number of the relevant option to execute the subsequent shell scripts/functions. 

Points to note:
* All entered customer details are converted to call lowercase when added to file to allow easier case insensitive search 
* The search for removing a customer is based only matching results of their name or alias. Other fields are not searched (intentional design choice)
* The search for a customer searches any of the fields and return any matches 
* The email customer allows a search, but only searches the email field of all customers (design choice). Also the email function has not been intensively tested as mailutils was set to the local system only when tested.


AUTHORS:
-----------------
Kevin Fan


VERSION or DATE:
------------------------------------
 26th April 2017
