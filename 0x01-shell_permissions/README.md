su betty -script that switches the current user to the user betty
whoami -script that prints the effective username of the current user.
echo "$USER" -script that prints the effective username of the current user.
groups -script that prints all the groups the current user is part of
sudo chown betty hello -script that changes the owner of the file hello to the user betty
touch hello -script that creates an empty file called hello
chmod u+x - script that adds execute permission to the owner of the file hello
chmod ug+x o+r hello -script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod +114 hello -cript that adds execute permission to the owner and

 the group owner, and read permission to other users, to the file hello
chmod +x hello -script that adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello -script that sets the permission to the file hello
chmod 753 hello -script that sets the mode of the file hello
chmod hello=olleh - script that sets the mode of the file hello the same as olleh’s mode
chmod --reference=olleh hello -script that sets the mode of the file hello the same a

s olleh’s mode
chmod -R +x -script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
chmod -R +x . -script that adds execute permission to all subdirectories of 

the current directory for the owner, the group owner and all other users. Regular files should not be changed.
mkdir chmod 751 my_dir - script that creates a directory called my_dir with permissions 751 in the working directory
chgrp school hello -script that changes the group owner to school for the file hello
mkdir -m 751 my_dir - script that creates a directory called my_dir wit

h permissions 751 in the working directory
chmod -R +X . -script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
chown vincent chgrp staff -script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
