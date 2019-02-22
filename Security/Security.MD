# Security

### **Commands**

~~~~
* Save command output to file
ls -al 
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
* Add permission
* add read permission to specific group for file or folder
* chmod g+r fiel name or folder name

* Example:
mkdir test_security
ls -all
chmod g+w test_security/

* Remove permission
* remove read permission to specific user for file or folder
* chmod u-r fiel name or folder name
chmod u-w test_security/
```

