This project directory contains shell scripts to manage user permissions to files,directories, among other permissions
0-iam_betty switches the current user to the user betty
1-who_am_i prints the effective username of the current user
2-groups prints all the groups the current user is part of
3-new_owner changes the owner of a file 'hello' to the user 'betty'
4-empty creates an empty file called 'hello'
5-execute adds execute permission to the owner of the file 'hello'
6-multiple_permissions adds execute permission to the owner and the group owner, and read permission to other users, to the file 'hello'
7-everybody adds execution permission to the owner, the group owner and the other users, to the file hello
8-Jame_Bond sets no permission to the owner and the group owner whereas other users get all the permissions
9-John_Doe set the permission of the 'hello' file to 753
10-mirror_permissions sets the mode of the 'hello' file to imitate the mode of the 'olleh' file
11-directories_permissions adds execute permission to all subdirectories of the current directroy for the owner, the group owner and all other users
12-directory_permissions creates a directory called 'my_dir with a permission of 751
13-change_group changes the group owner of 'hello' to 'school'
100-change_owner_and_group change the owner and group owner of all the contents of the working directory to vincent and staff respectively
101-symbolic_link_permissions changes the owner and group owner of '_hello' symbolink link to vincent and staff respectively
102-if_only changes the owner of 'hello' to 'betty' only if it is currently owned by 'guillaume'
103-Star_Wars plays the StarWars IV episode in the terminal
