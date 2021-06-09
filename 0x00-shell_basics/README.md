Shell Commands

pwd => this command print working directory this shell commnad is used for printing the current working directory

ls => this command lists the content of the current working directory

cd => this command used for changeing directory

ls -l => used for listing current directory content in a long format for displaying size date and time user and permission

ls -la => this command is the same as the previous one except now it displays hidden file and directories too

ls -ln => this commnad is used to display content of the directory in long format and used numerical data for user and group ID

mkdir /tmp/holberton => this command is used to create holberton directory in /tmp directory

mv /tmp/betty /tmp/holberton => this command is used to move the file betty to /tmp/holberton directory

rm /tmp/holberton/betty => this command is used to delete the file betty from /tmp/holberton directory

rm -r /tmp/holberton => this command is used to delete holberton directory form /tmp

cd - => this command is used to change the working directory to the previous one

ls ./ ../ /boot -la => this command is used to display current working directories and parent directory content including hidden files and /boot directory content in long format

file /tmp/iamafile => this command is used to display the type of file in /tmp/iamafile

ln -s /bin/ls _ls_ => this command is used to create a symbolic link called _ls_ for /bin/ls

cp -u ./*.html ../ => this command copy html files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory

mv [[:upper:]]* /tmp/u => this command moves all files that start with an upper case latter to the directory /tmp/u

rm *~ => this command deletes all files that ends with character ~

mkdir welcome welcome/to welcome/to/holberton => this commands are used to create a tree welcome/to/holberton directory in the current working directory
