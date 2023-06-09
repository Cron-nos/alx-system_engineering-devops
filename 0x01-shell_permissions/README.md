==>Description of what these scripts do<==


#!/bin/bash
su betty    ==>"Create a script that switches the current user to the
 user betty."<==


#!/bin/bash
id -un      ==>"a script that prints the effective username of the c
urrent user."<==


#!/bin/bash
groups    ==>"a script that prints all the groups the current user 
is part of."<==


#!/bin/bash
chown betty hello    ==>"a script that changes the owner of the file 
hello to the user betty."<==


#!/bin/bash
touch hello    ==>"a script that creates an empty file called hello."<==


#!/bin/bash
chmod u+x hello    ==>"a script that adds execute permission to the 
owner of the file hello."<==


#!/bin/bash
chmod u+x g+x o+r hello    ==>"a script that adds execute permission 
to the owner and the group owner, and read permission to other users,
 to the file hello."<==


#!/bin/bash
chmod a+x hello    ==>" a script that adds execution permission to 
the owner, the group owner and the other users, to the file hello"<==


#!/bin/bash
chmod 007 hello    ==>"a script that sets the permission to the file
 hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions"<==


#!/bin/bash
chmod 753 hello    ==>" a script that sets the mode of the file 
hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello"<==


#!/bin/bash
chmod --reference=olleh hello   ==>"a script that sets the mode
 of the file hello the same as olleh’s mode."<==


#!/bin/bash
chmod -R ugo+X .     ==>"a script that adds execute permission
 to all subdirectories of the current directory for the owner, 
the group owner and all other users.
Regular files should not be changed."<==

#!/bin/bash
mkdir -m 751 my_dir  ==>" a script that creates a directory 
called my_dir with permissions 751 in the working directory."<==

#!/bin/bash
chgrp school hello   ==>" a script that changes the group owner
 to school for the file hello"<==

#!/bin/bash
chown -hR vincent:staff .    ==>"a script that changes the owner
 to vincent and the group owner to staff for all the files and 
directories in the working directory."<==

#!/bin/bash
chown -hR vincent:staff _hello    ==>" a script that changes the
 owner and the group owner of _hello to vincent and staff respectively."<==

#!/bin/bash
chown ---from=guillaume betty hello    ==>"a script that will play
 the StarWars IV episode in the terminal."<==

#!/bin/bash
telnet towel.blinkenlights.ni    ==>"a script that will play the
 StarWars IV episode in the terminal."<==

