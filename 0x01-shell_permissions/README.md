su betty=change current user to betty
whoami=display current user name
groups=list  all groups user is in
sudo find / hello -exec chown betty {} \;=changes file hellos ownership from unknown dir to betty
touch hello=create a new empty file hello
chmod u+x hello=add execution permission to owner of hello
chmod ugo+x hello=add execution permission to hello users
chmod ug-rwx,o+rwx hello=removing all permissions from owner and group and giving others all permissions
chmod u+rwx,g+rx'o-r hello=adding all permissions to the owner,read exucute permission to group and removing read permission from others

