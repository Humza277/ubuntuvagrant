-Where am i - pwd - prints working directory 
-who am i - who - tells you the user and the time
-what do i have - ls- lists everything in the current directory
-hidden files - "ls -a" - tells you about the hidden files in the folder 
-find out the os - uname - tells you the name of the current os in linux 
-to clear the screen - clear - clears the screen
-create a file - touch - 'filenamehere.txt' - makes a file
-make a directory - mkdir 'directory name here' -  makes a directory 
-change a directory - 'cd ..' goes up a directory, 'cd directory' moves to that directory
-change to super user - sudo su - changes to super user 
-who is useing the machine - id - shows who is on the machine
-how to print cmd - echo - prints the command line
-to remove su - exit - exit to normal user 
-how to install packages - sudo apt-get install - installs the desired oackage 

Manipulating files/directories
learning to move files from local machine to the virtual machine
to do so we use the sink_files feature in vagrant
Error handling
running the vm this morning returned the error that "the vm was creatred with a user that doesnt match the current user
check hidden files - using the command ls -a
remove .vagrant file
Communications with developers - to understand requirements
what language is used to build the app
what framework has been used - mvc, react(front-end)
what are the dependencies and which ones have been included and which ones are needed
what will the app look like
install dependencies on ruby
install bundler in root mode using sudo -i
exit sudo and run the command bundle to download and install dependencies
run the test rake test
gives you the instructions to pass all the test
enter the vm

sudo apt-get updates

sudo apt-get install "package"

sudo apt-get upgrade

systemctl status nginx (name of the program)

go back to vm install node.js

use curl to install packages that or not in a package directory

in order to install pm2

install nom first in sudo

npm package manager for node

bash scripting
bash scripts can help us automate processes .sh means it is an executable file
chmod - change mode on linux bash - make files executable +x name_of_file

syntax to make a file executable +x
to run the executable file: ./name_of_file
created an bash script which downloaded nginx again onto our device
-#!/bin/bash

sudo apt-get update
sudo apt-get install nginx
sudo apt-get upgrade


chmod +rwx filename to add permissions.
chmod -rwx directoryname to remove permissions.
chmod +x filename to allow executable permissions.
chmod -wx filename to take out write and executable permissions.
Note that “r” is for read, “w” is for write, and “x” is for execute. 

This only changes the permissions for the owner of the file.
