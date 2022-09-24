# MacChanger
 
 What is this script?
 This is a simple MAC address changer created for Linux systems.

How to use the script?

The user can chose which interface he wants to change the MAC address (-i, --interface) and then provide the desired MAC address (-m, --mac);
If the user don't pass any arguments, the script will ask for the user to input the pending information;
This script needs to run as sudo or root, otherwise the user will get an error;
This code is meant to work with Python3.

Specifing the interface and the MAC address:
sudo python3 MacChanger.py -i eth0 -m 00:11:22:33:44:55


