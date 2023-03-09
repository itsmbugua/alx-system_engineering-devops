1.su betty=change current user to betty
2.whoami=display current user name
3.groups=list  all groups user is in
4.sudo find / hello -exec chown betty {} \;=changes file hellos ownership from unknown dir to betty
5.touch hello=create a new empty file hello
6.chmod u+x hello=add execution permission to owner of hello
7.chmod ugo+x hello=add execution permission to hello users
8.chmod ug-rwx,o+rwx hello=removing all permissions from owner and group and giving others all permissions
9.chmod u+rwx,g+rx'o-r hello=adding all permissions to the owner,read exucute permission to group and removing read permission from others
10.chmod --reference=hello olleh =copying permissions from hello to olleh
11.chmod a+X * =give execution permission to only the dir in the working dir leaving the files
12.mkdir -m 751 my_dir =create a dir my_dir and give permissions 751
13.chgrp school hello=change the group owner of file hello 
