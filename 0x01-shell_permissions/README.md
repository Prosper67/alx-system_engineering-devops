Ox01-shell_permisions

su  betty 	switch the current user to a new user betty

whoami 		print the effective username of the current user

id -nG		prints all the groups of the curremt user
sudo chown betty hello 	change the owner of file hello to user betty
touch hello 	create an empty file called hello
chmod u+x hello 	Add execution permission
chmod ug+x o+r execite permission te  the owner
chmod a+x hello
chmod 007 hello 	 file permissions
chmod 753 hello 	file permissions
chmod --reference =olleh hello 	Mirror permissions
chmod +X* 	directories permissions
mkdir -m 751 my_dir directory permissions
chgrp school hello group owner change
sudo chown vincent:staff* 	change file ownerships
