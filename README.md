1.
How do you remote login to a machine ?
Create a user testuser with some password and try to ssh using that user?
Try enabling passwordless ssh using certs?
Create a file with “root” user and verify the permissions of the file.
Change the ownership of the file to the newly created testuser.
Now delete the test user.
========================================================================
2
Install any package of your choice lets (ex mariadb / nginx / elasticsearch )
uninstall the same.
Verify if some config files of the same are present if yes ? then how will you remove them (using package manager only)?
========================================================================
3
Check how much free disk is available and also ensure that the command prints the files system of the mount points ?
Check how much disk is used by a particular directory ?
List all the files in a directory along with the hidden files?
How do you check the ram in the system ?
How to list all the open ports on the server ?
Create a file and ensure that even root cannot edit it.

========================================================================
4
Read up about systemd.
How to start, stop and reload a service in systemd?
Create one service in systemd then try to manage it via systemctl commands
========================================================================
5
Try attaching a disk to the VM ?
Format (with any file system of ur choice) and mount the disk on /testmount.?
Reboot the machine and ensure that the mount is persisted across reboots.?
Unmount the mountpoint and play around with Logical Volume Manager?
Create PV, VG and LV.

=======================================================================
6
Write a bash script to print the numbers from 1 to 100, but print PHONE if the number is divisible by 3 and print PE if the number is divisible by 5.
Write a bash script to find and replace a string in a file.X
Write a bash script to check if a file exists or not, if it does not exist then create the file. ( this file creation must happen via function). Otherwise print that file exists. Similarly create a logic if a directory exists or not.
Write a bash script to demonstrate the case statement.# Taskday_Assignment

