#!/bin/bash
0. pwd: The script prints the absolute path name of the current working directory.
1. ls: Displays the contents list of your current directory.
2. cd: changes the working directory to the user’s home directory.
3. ls -l: Displays current directory contents in a long format.
4. ls -la:Display current directory contents, including hidden files in a long format.
5. ls -l -n -a: Displays current directory contents in long format with user and group IDs displayed numerically and also shows hidden files.
6. mkdir /tmp/my_first_directory: Creates a directory named my_first_directory in the /tmp/ directory.
7. mv /tmp/betty /tmp/my_first_directory: Moves the file betty from /tmp/ to /tmp/my_first_directory.
8. rm /tmp/my_first_directory/betty: Deletes the file betty in/tmp/my_first_directory/
9. rm -r /tmp/my_first_directory: Deletes my_first_directory in /tmp.
10. cd -: Changes the working directory to the previous one.
11. ls -la . .. /boot: Displays a list of all files (including hidden files) in the current directory and in the bood directory in long format.
12. file /tmp/iamafile: Prints the type of the file named iamafile in /tmp.
13. ln -s /bin/ls __ls__: Creates a symbolic link called __ls__ to /bin/ls in the current directory.
14. cp -u *.html ..: Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
15. mv [[:upper:]]* /tmp/u: Moves all files beginning with an uppercase letter to the directory /tmp/u.
16. rm *~: deletes all files in the current working directory that end with the character ~.
17. mkdir -p welcome/to/school: creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
18. ls -xamp: lists all the files and directories of the current directory, separated by commas (,).
19. 0 string SCHOOL School data
!:mime School: Creates a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
