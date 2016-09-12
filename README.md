# update-all
Bash script with all the update commands for Ubuntu.

This script will:

1. update the package list
2. upgrade new packages
3. autoremove old packages
 
...without asking _yes/no_. ;-)

##Howto

__Prepare:__

1. Put the file _update-all.sh_ on your Ubuntu desktop or server.
2. Change owner user and group of the script to root: ```sudo chown root:root update-all.sh```
3. Make the file executable: ```sudo chmod +x update-all.sh```

__Run:__

Open terminal where the file is and put: ```sudo ./update-all.sh```
 
__Have fun!__
