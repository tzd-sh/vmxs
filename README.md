# vmxs
VMXS: Vagrant list access info of running VMs

Written by: Zheng-Da Tan

Pre-requisites: This script is quite useless without Perl and Vagrant

This is a simple Perl script for Vagrant users to list access information (IP Address, Username and Local SSH Port Number) of all their running VMs.

To use, simply download 'vmxs', place it in a folder in your $PATH, and make it executable (for example, 'chmod 755').

Example:
```
$ vmxs
======= ======== ========= ====== ======== =====================================
ID      NAME     DIRECTORY PORT   USER     ADDRESSES
======= ======== ========= ====== ======== =====================================
1a2b3c4 default  instance  L_2201 ubuntu   10.0.2.15 10.0.1.17 172.17.0.1
5d6e7f8 backend  multi     L_2222 ubuntu   10.0.2.15 10.99.83.20
9a0b1c2 frontend multi     L_2200 ubuntu   10.0.2.15 192.168.1.125 10.99.83.10
```
