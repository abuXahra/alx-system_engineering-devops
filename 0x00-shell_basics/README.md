- script 0-current_working_directory:
  prints the absolute path name of the current working directory

- Script 1-listit : 
  Display the contents list of the current directory

- Script 2-bring_me_home: 
Take the user from working directory to the home directory

- Script 3-listfiles: 
Display current directory contents in along format

- Script 4-listmorefiles: 
Display current directory contents including the hidden files

-Script 5-listfilesdigitonly: Display current directory contents - Long format - with uuser and group IDs displayed numerically - And hidden files (starting with .)

-Script 6-firstdirectory: Create a directory my_first_directory in the /temp/ directory

-Script 7-movethatfile: move the file betty from /tmp/ to /tmp/my_first_directory

-Script 8-firstdelet: Delete the file betty from /tmp/my_first_directory/

Script 9-firstdeletion: Delete the my_first_directory that is in the /tmp directory

Script 10-back: Changes the working directory to the previouse one

Script 11-lists: Lists all files (even once with names beginning with a period character, wich are normally hidden) in the current directory and the parent of the working directory and /boot

Script 12-file_type prints the type of the named iamafile in the /tmp directory

- Script 13-symbolic_link: Create a sumbolic link to /bin/ls, named ls. The symbolic link shold be created in the current working directory

- Sript 14-copy_html: Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

- script 100-lets_move:
Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

- script 101-clean_emacs
Create a script that deletes all files in the current working directory that end with the character ~.

- script 102tree:
Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

- script 103-commas:
Write a command that lists all the files and directories of the current directory, separated by commas (,).

	Directory names should end with a slash (/)
	Files and directories starting with a dot (.) should be listed
	The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
	Only digits and letters are used to sort; Digits should come first
   	You can assume that all the files we will test with will have at least one letter or one digit
	The listing should end with a new line


- Script school.magic:
Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

