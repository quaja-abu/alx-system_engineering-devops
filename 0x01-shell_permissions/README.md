shell permissions

sudo -u betty => this command is used to change the current user to the user betty assuming the user betty will exist

whoami => this command is used to print effective username of the current user

groups => this command is used to print all the groups the current user is part of

chown betty hello => this command is used to change hello file owner to betty

touch hello => this command is used to create an empty file called hello

chmod u+x hello => this command is used to add execute permission to the owner of the file hello

chmod ug+x,o+r hello => this command is used to add execute permission for user and group owner and a read permission for other for hello file in the working directory"

chmod 777 hello => this command is used to add exectue permission to the owner, group and other user for the file hello

chmod 007 hello => this command is used to add no permission to owner and group and all the permission for other users for the file hello"

chmod 753 hello => this command is used to add -rwxr-x-wx permission for the file hello"

chmod --reference=olleh hello => this command is used to sets the mode of the file hello the same as olleh
