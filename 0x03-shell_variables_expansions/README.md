#!/bin/bash
0. alias ls="rm *": Create a script that creates an alias. Name: ls and Value: rm *.
1. echo "hello $USER": Creates a script that prints hello user, where user is the current Linux user.
2. export PATH=$PATH:/action: Adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
3. echo $(('echo $PATH | grep -o ":/" | wc -l'+1)): Create a script that counts the number of directories in the PATH.
4. printenv: Creates a script that lists environment variables. 
5. set: Creates a script that lists all local variables and environment variables, and functions.
6. Best="School":Create a script that creates a new local variable. Name: BEST and Value: School.
7. echo $((2#$BEST SCHOOL)): Create a script that creates a new global variable. Name: BEST and Value: School
8. echo $(($TRUEKNOWLEDGE + 128)): prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
9. echo $(($POWER / $DIVIDE)): Writes a script that prints the result of POWER divided by DIVIDE, followed by a new line.
10. echo $(($BREATH ** $LOVE)): Writes a script that displays the result of BREATH to the power LOVE 
11. echo $((2#$BINARY)): converts a number from base 2 to base 10.
12. echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo": Create a script that prints all possible combinations of two letters, except oo.
13. printf '%.2f\n' $NUM:  prints a number with two decimal places, followed by a new line.
14.  
