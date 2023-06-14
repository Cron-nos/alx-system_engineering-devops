### 0x03-shell_variables_expansions
#!/bin/bash
alias ls ='rm *'
#script that creates an alias.

#!/bin/bash
echo "hello $USER"
#script that prints hello user, where user is the current Linux user.

#!/bin/bash
export PATH=$PATH:/action
#script that adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program

#!/bin/bash
echo $((' echo $PATH | grep -o ":/" | wc -1 ' +1))
#script that counts the number of directories in the PATH.

#!/bin/bash
printenv
#script that lists environment variables.

#!/bin/bash
set
#script that lists all local variables and environment variables, and functions.

#!/bin/bash
BEST='School'
#script that creates a new local variable.

#!/bin/bash
export BEST='School'
#script that creates a new global variable.

#!/bin/bash
echo $((TRUEKNOWLEDGE+128))
#script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

#!/bin/bash
echo $(($POWER/$DIVIDE))
#script that prints the result of POWER divided by DIVIDE, followed by a new line.

#!/bin/bash
echo $(($BREATH**LOVE))
#script that displays the result of BREATH to the power LOVE

#!/bin/bash
echo $(($2#$BINARY))
#script that converts a number from base 2 to base 10.

#!/bin/bash
echo {a..z}{a..z} | tr " " " \n | grep -v "oo"
#script that prints all possible combinations of two letters, except oo.

#!/bin/bash
printf  "%.2f" $NUM | sort
#script that prints a number with two decimal places, followed by a new line.The number will be stored in the environment variable NUM.





