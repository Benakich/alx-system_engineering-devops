Script 1 - Change User
Script 2 - Print effective username of current user
Script 3 - print all the groups current user is part of
Script 4 - Change file owner
Script 5 - create empty file
Script 6 - add execution permission
Script 7 - add more permissions
Script 8 - add more permission
Script 9 - Set permission
Script 10 - Set more permission
Script 11 - set more permission
Script 12 - set more permission
Script 13 - set directory permission
Script 14 - Change group owner


Copy File Permissions to Another File
To copy file permissions from one file to another file, use chmod command with the --reference switch in the following syntax, where reference_file is the file from which permissions will be copied rather than specifying mode (i.e octal or numerical mode permissions) for file.

$ chmod --reference=reference_file file
For example,

$ ls -l users.list
$ ls -l keys.list
$ sudo chmod --reference=users.list keys.list
$ ls -l keys.list
