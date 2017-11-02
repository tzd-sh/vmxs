# vmxs
VMXS: Vagrant list access info of running VMs

Written by: Zheng-Da Tan

Pre-requisites: This script is quite useless without Perl and Vagrant

This is a simple Perl script for Vagrant users to list access information (IP Address, Username and Local Port Number) of all their running VMs.

To use, simply download 'vmxs', place it in a folder in your $PATH, and make it executable (for example, 'chmod 755').

Example:
```
$ vmxs
======== ========== ====== ======== ========================
ID       DIRECTORY  L_PORT USER     IP ADDRESSES
======== ========== ====== ======== ========================
1a2b3c4  instance1  2222   vagrant  10.0.2.15 192.168.1.115
5d6e7f8  instance2  2200   ubuntu   10.0.2.15 192.168.1.109
```
