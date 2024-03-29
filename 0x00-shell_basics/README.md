## 0x00-shell_basics

### Question 0

Write a script that prints the absolute path name of the current working directory.

### Question 1

Display the contents list of your current directory.

### Question 2

Write a script that changes the working directory to the user’s home directory.
You are not allowed to use any shell variables

### Question 3

Display current directory contents in a long format

### Question 4

Display current directory contents, including hidden files (starting with .). Use the long format.

### Question 5

Display current directory contents.
- Long format
- with user and group IDs displayed numerically
- And hidden files (starting with .)

### Question 6

Create a script that creates a directory named my_first_directory in the /tmp/ directory.

### Question 7

Move the file betty from /tmp/ to /tmp/my_first_directory.

### Question 8

Delete the file betty.
- The file betty is in /tmp/my_first_directory

### Question 9

Delete the directory my_first_directory that is in the /tmp directory.

### Question 10

Write a script that changes the working directory to the previous one.

### Question 11

Write a script that lists all files (even ones with names beginning 
with a period character, which are normally hidden) in the current directory
and the parent of the working directory and the /boot directory (in this order), in long format.

### Question 12

Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

### Question 13

Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

### Question 14

Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

### Question 15

Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

### Question 16

Create a script that deletes all files in the current working directory that end with the character ~.

### Question 17

Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
You are only allowed to use two spaces (and lines) in your script, not more.

### Question 18

Write a command that lists all the files and directories of the current directory, separated by commas (,).
- Directory names should end with a slash (/)
- Files and directories starting with a dot (.) should be listed
- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
- Only digits and letters are used to sort; Digits should come first
- You can assume that all the files we will test with will have at least one letter or one digit
- The listing should end with a new line


### Question 19

Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
