# Security

### **Commands**

```
* sudo command used before any linux command to give super user (administartot privilegs) to this command while running it and It prompts you for your personal password.

* Example:
sudo apt-get update

* You can change the current user to sudo for somtimes (act as root user is very risky)
* once you finish your task, enter exit

sudo su
```

```
* create new user 
* It reqiure to create password and fill some information about the new user
* by default the system will create new group and this user to it, the name of group will * be the same user name.
sudo adduser newusername

* get details of specific user
id username

* Add new group
Sudo groupadd newgroupname

*Add user “username” to group “groupname”
sudo usermod -a -G groupname username

* get list of users in specfic group by accessing group file
nano /etc/group
or
grep 'groupname' /etc/group

* change the current user to another user (password is required)
* click exit to back to your user or use same command to back to your user
su username


* pass command as of another user
su username -c command

* get list of users
compgen -u

* get list of groups
compgen -g

* Get list of groups of specific user name
groups username

* delete group
sudo groupdel groupname

* delete user 
sudo userdel username
```

~~~~
* Get list of folders and files with its security
ls -al 
* Results
drw-rwx--x
-rw-rwx--x

* Folder permissing is start by d
* File permission is start by -
* Each file or folder has 3 Permission Target : (u = User g = Group o = Other)
* Each permission target has 3 Permission Types : (r = Read (4) w = Write (2) x = Execute (1) )
* Example:
  drw-rwx--x
  1- this permission for folder not file
  2- user permission is read + write + execute is not allowed
  3- group permission is read + write + execute
  4- other permssion allow only execute
~~~~

```
* Add permission using (+/- u\g\o)
* add read permission to specific group for file or folder
* chmod g+r fiel name or folder name

* Example:
mkdir test_security
ls -all
chmod g+w test_security/

* Remove permission (+/- u\g\o)
* remove read permission to specific user for file or folder
* chmod u-r fiel name or folder name
chmod u-w test_security/
```

```
* Add permission using numbers for folder or file
* 4 = Read \ Write = 2 \ Execute = 1
* To add full access to user + only read & execute for group + only execute for other
chmod 751 test_security/

* Add permission using numbers for folder and its subfolders
chmod 751 -R test_security/

```

[Back](https://github.com/bassammannaa/Ubuntu-Training/blob/master/README.md)


