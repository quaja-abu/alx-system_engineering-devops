shell permissions

sudo -u betty => this command is used to change the current user to the user betty assuming the user betty will exist

echo $USER => this command is used to print effective username of teh current user

groups => this command is used to print all the groups the current user is part of

chown betty hello => this command is used to change hello file owner to betty

touch hello => this command is used to create an empty file called hello

chmod u+x hello => this command is used to add execute permission to the owner of the file hello
