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

An a simple email function is also requested by the company.


HOW TO START THIS PROJECT:
-------------------------------
To start the project, download/clone the repository and browse to directory using a terminal on a linux based system.

From the terminal, run the ./Menu to run the Menu script and which will bring you to the Menu of the project.

The scripts was granted read, write and execute privileges on the ubuntu test system. If the script do not execute, give read, write and execute priviges to the scripts with the command:

chmod 755 nameOfScript


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
* All entered customer details are converted to call lowercase when added to file to allow easier case insensitive search (for awk searches mainly).
* The search for removing a customer is based only matching results of their name or alias. Other fields are not searched (intentional design choice). A possible improvement would be to allow the user to select which field to search for like in the EmailScript.
* The search for a customer searches any of the fields and return any matches (uses a grep search instead of awk).
* The email script search allows users to select which search field, i.e. name, and only searches that column for matches. Only the emails of the matched rows matched, instead of both the email and name, is returned. This is prevent uses another awk search on this display to select only the emails.


AUTHORS:
-----------------
Kevin Fan


VERSION or DATE:
------------------------------------
 27th April 2017
