#!/bin/bash
0. alias ls="rm *": Create a script that creates an alias. Name: ls and Value: rm *.
1. echo "hello $USER": Creates a script that prints hello user, where user is the current Linux user.
2. export PATH=$PATH:/action: Adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
3. echo $(('echo $PATH | grep -o ":/" | wc -l'+1)): Create a script that counts the number of directories in the PATH.
4. printenv: Creates a script that lists environment variables. 
5. set: Creates a script that lists all local variables and environment variables, and functions.
6. 
