# Linux Notes

This document is a quick reference for notes and command that are used in Linux

## Commands

* cd <path> - Change Directory
* mkdir <dirname> - make a directory
* touch <filename> - create an empty file
* tail <filename> - lists last 10 lines of file
* head <filename> - Lists first 10 lines of file


### deleting files

* rm <filename> - removes file
* rmdir <directory> - removes empty directory
* rm -r <directory> - recursivly removes directories and files.prompts for approval of deletion. Use with **Use with Caution** 

## Linux paths of interest

[File Hierarchy standard](https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard)

* / - root, all directories exist below this 
* /home - directory where user directories exist at
* /root - roots home directory
* /etc - system configuration files
* /sbin - applications that require higher permissions than user, more than likely used by root or admins
* /bin - General applications useable by anyone on the system
* /usr/bin - same as above
* /var - variable directory where files that change a lot exist. Log files should reside in this directory
* /var/log - where system log files exisit. 

