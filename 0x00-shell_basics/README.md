#!/bin/bash
pwd "prints the absolute path name of the current working directory."

#!/bin/bash
ls  "Display the contents list of your current directory."

#!/bin/bash
cd ~ "changes the working directory to the user’s home directory."

#!/bin/bash
ls -l "Display current directory contents in a long format."

#!/bin/bash
ls -al "Display current directory contents, including hidden files (starting with .). Use the long format."

#!/bin/bash
ls -al "Display current directory contents.

-Long format
-with user and group IDs displayed numerically
-And hidden files (starting with .)"

#!/bin/bash
mkdir /tmp/my_first_directory/ "creates a directory named my_first_directory in the /tmp/ directory."

#!/bin/bash
mv /tmp/betty /tmp/my_first_directory/betty "Move the file betty from /tmp/ to /tmp/my_first_directory."

#!/bin/bash
rm /tmp/my_first_directory/betty "Delete the file betty."

#!/bin/bash
rm -rf /tmp/my_first_directory "Delete the directory my_first_directory that is in the /tmp directory."

#!/bin/bash
cd - "changes the working directory to the previous one."

#!/bin/bash
ls -la . .. /boot "lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format."

#!/bin/bash
file /tmp/iamafile   " prints the type of the file named iamafile."

#!/bin/bash
ln -s /bin/ls __ls__  "Create a symbolic link to /bin/ls, named __ls__"

#!/bin/bash
cp -u *.htm .. "copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory."

#!/bin/bash
mv [[:upper:]]* /tmp/u  ""

#!/bin/bash
rm *~

#!/bin/bash
mkdir -p welcome/to/school

#!/bin/bash
ls -xamp

0 string HOLBERTON Holberton data
!:mime Holberton
