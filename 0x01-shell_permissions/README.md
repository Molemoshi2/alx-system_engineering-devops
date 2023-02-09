#!/bin/bash
su betty - switches current user to user betty
whoami - prints the username of current user
groups - prints all the groups the current user is part of.
README.md sudo chown betty hello - changes the current owner of the file hello to user betty
touch hello - creates an empty file hello
chmod u+x hello - gives owner execute permission
chmod ug+x,o+r hello -  execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello - adds execution permission to the owner, the group owner and the other users, to the file hello
