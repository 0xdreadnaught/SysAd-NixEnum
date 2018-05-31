# SysAd-NixEnum
A Linux system enumeration script for system admins.
 Gathers information on the following:
 
 System:
 - current user/hostname
 - operating system and kernel versions
 - system date and uptime
 - logged in users
 - all users that have used the system
 
 Resources:
 - a single top snapshot
 
 Services:
 - checks puppet status (can be replaced with chef, ansible, or any other important services depending on SA needs
 
 Networking:
 - an ifconfig of the primary NIC
 - a tcpdump on the primary interface
 
 Devices:
 -lsusb
 -lsblk
 -lspci
 
 Storage:
 - df -h
 - fdisk -l
 - open files
 - last modified files
 
 Reboot/Shutdown History
 - currenty shows them in two separate lists. This will be fixed to give better info for troubleshooting time related problems
