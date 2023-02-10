#!/bin/bash
0. su betty: switches the current user to the user betty.
1. id -un: prints the effective username of the current user.
2. groups: prints all the groups the current user is part of.
3. sudo chown betty hello: changes the owner of the file hello to the user betty.
4. touch hello: creates an empty file called hello.
5. chmod u+x hello: adds execute permission to the owner of the file hello.
6. chmod u+x,g+x,o+r hello: adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7. chmod ugo+x hello: adds execution permission to the owner, the group owner and the other users, to the file hello.
8. chmod 007 hello: sets the permission of the file hello to give the owner and group no permission at all but give other users all the permissions.
9. chmod 753 hello: sets the mode of the file hello to -rwxr-x-wx.
