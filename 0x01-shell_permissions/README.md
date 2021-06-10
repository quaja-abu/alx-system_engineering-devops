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

find ./ -type d -exec chmod 711 {} \; => this commad is used to add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed

mkdir -m 751 dir_holberton => this command is used to create a directory dir_holberton with 751 permission

chown :holberton hello => this command is used to change the group owner to holberton for the file hello

chown -R betty:holberton . => this command is used to change the owner to betty and group owner to holberton for all files and directories

chown -h betty:holberton _hello => this command is used to change the owner and group owner of symbolic link _hello to betty and holberton

chown --from=guillaume: betty hello => this command is used to change the owner of the file hello to betty only if it is owned by the user guillaume
