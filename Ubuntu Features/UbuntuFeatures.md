# Ubuntu Features

### Linux files System Hierarchy

![FileSystem](https://github.com/bassammannaa/Ubuntu-Training/blob/master/Ubuntu%20Features/FileSystem.png)


<u>**" / "**</u> <u>**- Root point**</u><BR/>
The /Root Directory, every single directory and file starts from the root directory .
Only the root user has the ability to write under the root directory.



**<u>/bin - User Binaries</u>**<BR/>
The binary executables and the common Linux commands needed to be used in single
user modes are Located in the /bin Directory. /bin also contains the commands that
are used by all users of the system.



**<u>/boot - Boot Loader Files</u>**<BR/>
All of the files needed to example your Linux kernels boot loader's configuration program configuration files boot the system are located in the /boot directory. For and the GRUB boot loader's files are located here, but the files aren't located here, they are located in /etc. , All are located in /etc .



**<u>/dev - Device Files</u>**<BR/>
hard disks , floppy , cd-rom , usb , all of these device files are located under /dev .



**<u>/etc - Configuration Files</u>**<BR/>

The configuration files required by all programs are located in /etc . It also contains
system-wide configuration files. /etc does not contain user-specific configuration
files; user-specific configuration files are located in each user's home directory.



**<u>/home - Home directories</u>**<BR/>
Home directories for all users are located in /home.



**<u>/lib - System libraries</u>**<BR/>
The library Files that support the binaries located in /bin and /sbin are located in /lib .



**<u>/mnt - Mount Directory</u>**<BR/>
When system administrators mount temporary file systems while using them, those
file systems are mounted by default on /mnt directory. However, file systems can be
mounted anywhere on the system.



**<u>/root</u>**<BR/>
/root is different from the " / " , the home directory of the user root is /root . The user
root is the administrator that has all authorities.



**<u>/sbin - System Binaries</u>**<BR/>
Like the /bin directory, the /sbin contains binary executable. For system maintenance
purposes, the Linux commands located in this directory are used typically by system
administrators.



**<u>/srv - Service Data</u>**<BR/>
Data for services provided by the system are located in /srv . For example if you are
using the Apache HTTP server to serve a website, then you will probably save or
store your website's files in a directory under the /srv directory.



**<u>/tmp - Temporary Files</u>**<BR/>
Temporary files created by system and users are located in /tmp . Note the the files in
this directory are automatically deleted when the system is rebooted .



**<u>/usr - User Programs</u>**<BR/>
Applications and files used by users are located in /usr .



**<u>/var - Variable Data Files</u>**<BR/>
The writable counterpart to the /usr directory is the / var directory. Everything
including log files that will be written to /usr (during normal operation) will be
automatically written to the /var directory .For example, Log files will be found in
/var/log.


