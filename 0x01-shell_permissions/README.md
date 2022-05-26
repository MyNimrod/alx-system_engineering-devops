#0x01-shell_permissions
0-iam_betty switches the current user to the user betty
1-who_am_i  prints the effective username of the current user
3-new_owner changes the owner of the file hello to the user betty
4-empty creates an empty file called hello
5-execute adds execute permission to the owner of the file hello
6-multiple_permissions adds u+x g+x o+r
7-everybody dds execution permission to u g o
8-James_Bond  set permission to u none g none o all
9-John_Doe  set permission to u rwx g r-x o -wx
10-mirror_permissions  set permission similar to file olleh
11-directories_permissions adds execute permission to all subdirectories of the current directory 
12-directory_permissions creates a directory called my_dir with permissions 751 in the working directory
13-change_group  changes the group owner to school for the file hello
100-change_owner_and_group changes the owner to vincent and group to staff for all files and directories
101-symbolic_link_permissions change owner and group for sym link
