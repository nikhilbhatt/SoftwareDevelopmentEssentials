# Linux Permission:-

* there are 3 types of users in Linux
1. User - who created the file/ owner of the file
2. Group - a person who is a part of a group can access the file
3. Other - anyone else


* to list the permssions use $ ls -l
1. drwxrwxrwx
		* d means directory and if instead of d there is - it means file. eg. -rwxrwxrwx
		* r means read permission
		* w means write permission
		* x means execute permssion
		* first rwx if for user second rwx is for group and third rwx is for other

* how to change the permission
1. Absolute method
2. symbolic method

* Absolute Method
1. This method change the permsission using a code for eg. chmod <permission no.> <filename>
2. How to calculate permission no. 
		* think user-group-other in a sequence.
		* for each user/group/other calculate a binary no from 0 to 7 in following way.
		* for read permission use 0/1 same for write and execute. convert the no. into decimal. e.g.110(read write execute respectively) converted to 6(means rw-)
		* now find out the no. for every user
		* ex. 777 (this will set all permissions for all users).
		* chmod 777 <filename>

* Symbolic method
1. This method is used when you have want to set/remove permission for only one type i.e. user/group/other
2. symbols are as follows:-
		* + add a permssion
		* - remove a permission
		* = override all previous permssions
3. Examples:-
		* chmod u+r  (add a read permission for user in the file)
		* chmod o-r (remove read permission for other)
		* chmod o=w (override all the previous permissions and set write permission only)	


* Change the owner and group of a file
1. chown user <filename>
2. chown user:group <filename>
3. chgrp group <filename>

* NOTE Use sudo before executing chown/chgrp commands

For more Information Here is the [link](https://www.guru99.com/file-permissions.html#:~:text=There%20are%20three%20user%20types,into%20Absolute%20and%20Symbolic%20mode)
