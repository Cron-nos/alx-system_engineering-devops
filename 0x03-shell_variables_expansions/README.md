0x03-shell_variables_expansions


0-alias
#!/bin/bash
alias ls ='rm *'
#script that creates an alias.
Name: ls
Value: rm *


1-hello_you
#!/bin/bash
echo "hello $USER"
#script that prints hello user, where user is the current Linux user.


2-path
#!/bin/bash
export PATH=$PATH:/action
#script that adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program

3-paths
#!/bin/bash
echo $((' echo $PATH | grep -o ":/" | wc -1 ' +1))
#script that counts the number of directories in the PATH.

4-global_variables
#!/bin/bash
printenv
#script that lists environment variables.


5-local_variables
#!/bin/bash
set
#script that lists all local variables and environment variables, and functions.



6-create_local_variable
#!/bin/bash
BEST='School'
#script that creates a new local variable.


7-create_global_variable
#!/bin/bash
exprt BEST='School'
#script that creates a new global variable.
Name: BEST
Value: School



8-true_knowledge
#!/bin/bash
echo $((TRUEKNOWLEDGE+128))
#script that prints the result of the addition of 128 with the value stored in 
the environment variable TRUEKNOWLEDGE, followed by a new line.


9-divide_and_rule
#!/bin/bash
echo $(($POWER/$DIVIDE))
#script that prints the result of POWER divided by DIVIDE, followed by a new line.


10-love_exponent_breath
#!/bin/bash
echo $(($BREATH**LOVE))
#script that displays the result of BREATH to the power LOVE


11-binary_to_decimal
#!/bin/bash
echo $(($2#$BINARY))
#script that converts a number from base 2 to base 10.


12-combinations
#!/bin/bash
echo {a..z}{a..z} | tr " " " \n | grep -v "oo"
#script that prints all possible combinations of two letters, except oo.


13-print_float
#!/bin/bash
printf  "%.2f" $NUM | sort
#script that prints a number with two decimal places, followed by a new line.
The number will be stored in the environment variable NUM.





