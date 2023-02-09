#!/bin/bash
su betty - switches current user to user betty
whoami - prints the username of current user
groups - prints all the groups the current user is part of.
README.md sudo chown betty hello - changes the current owner of the file hello to user betty
touch hello - creates an empty file hello
chmod u+x hello - gives owner execute permission
chmod ug+x,o+r hello -  execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello - adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello - only gives permission to all other users and not owner and group
chmod 753 hello - sets the mode of the file hello to -rwxr-x-wx
chmod --reference-olleh hello - sets the mode of the file hello the same as olleh’s mode.
chmod -R +X . - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
 mkdir -m 751 my_dir - script that creates a directory called my_dir with permissions 751 in the working directory.
 chgrp school hello - changes the group owner to school for the file hello
chown vincent:staff * - changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown -h vincent:staff _hello - changes the owner and the group owner of _hello to vincent and staff respectively
