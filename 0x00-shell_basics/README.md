This is the readme for this folder
The solutions to each of the 19 tasks are in here

Task name: Where am I?
File name: 0-current_working_directory
Task Description: Write a script that prints the absolute path name of the current working directory.

Task name: What’s in there?
File name: 1-listit
Task Description: Display the contents list of your current directory.

Task name: There is no place like home
File name: 2-bring_me_home
Task Description: Write a script that changes the working directory to the user’s home directory.
You are not allowed to use any shell variables

Task name: The long format
File name: 3-listfiles
Task Description: Display current directory contents in a long format

Task name: Hidden files
File name: 4-listmorefiles
Task Description: Display current directory contents, including hidden files (starting with .). Use the long format.

Task name: I love numbers
File name: 5-listfilesdigitonly
Task Description: Display current directory contents.
Long format
with user and group IDs displayed numerically
And hidden files (starting with .)

Task name: Welcome
File name: 6-firstdirectory
Task Description: Create a script that creates a directory named my_first_directory in the /tmp/ directory.

Task name: Betty in my first directory
File name: 7-movethatfile
Task Description: Move the file betty from /tmp/ to /tmp/my_first_directory.

Task name: Bye bye Betty
File name: 8-firstdelete
Task Description: Delete the file betty.
The file betty is in /tmp/my_first_directory

Task name: Bye bye My first directory
File name: 9-firstdirdeletion
Task Description: Delete the directory my_first_directory that is in the /tmp directory.

Task name: Back to the future
File name: 10-back
Task Description: Write a script that changes the working directory to the previous one.

Task name:  Lists
File name: 11-lists
Task Description: Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

Task name: File type
File name: 12-file_type
Task Description: Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

Task name: We are symbols, and inhabit symbols
File name: 13-symbolic_link
Task Description: Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

Task name: Copy HTML files
File name: 14-copy_html
Task Description: Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
You can consider that all HTML files have the extension .html

Task name: Let’s move
File name: 100-lets_move
Task Description: Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
You can assume that the directory /tmp/u will exist when we will run your script

Task name: Clean Emacs
File name: 101-clean_emacs
Task Description: Create a script that deletes all files in the current working directory that end with the character ~.

Task name: Tree
File name: 102-tree
Task Description: Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
You are only allowed to use two spaces (and lines) in your script, not more.

Task name: Life is a series of commas, not periods 
File name: 103-commas
Task Description: Write a command that lists all the files and directories of the current directory, separated by commas (,).
Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line

Task name: File type: School
File name: school.mgc
Task Description: Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
