# Ubuntu Features

### Linux files System Hierarchy



| Folder Name                     | Description                                                  |
| ------------------------------- | ------------------------------------------------------------ |
| /                               | The /Root Directory, every single directory and file starts from the root directory .    Only the root user has the ability to write under the root directory. |
| /bin          (User Binaries)   | The binary executables and the common Linux commands needed to be used in single<br/>user modes are Located in the /bin Directory. /bin also contains the commands that
are used by all users of the system. |
| /boot       (Boot Loader Files) | All of the files needed to example your Linux kernels boot loader's Configuration, program configuration files boot the system are located in the /boot directory. For
and the GRUB boot loader's files are located here, but the
files aren't located here, they are located in /etc. , All
are located in /etc . |
| /dev      (Device Files)        | hard disks , floppy , cd-rom , usb , all of these device files are located under /dev . |
| /etc (Configuration Files)      | The configuration files required by all programs are located in /etc . It also contains<br/>system-wide configuration files. /etc does not contain user-specific configuration
files; user-specific configuration files are located in each user's home directory. |
| /home  (Home directories)       | Home directories for all users are located in /home.         |
| /lib        (System libraries)  | The library Files that support the binaries located in /bin and /sbin are located in /lib . |
| /mnt      (Mount Directory)     | When system administrators mount temporary file systems while using them, those<br/>file systems are mounted by default on /mnt directory. However, file systems can be
mounted anywhere on the system. |
| /root                           | /root is different from the " / " , the home directory of the user root is /root . The user<br/>root is the administrator that has all authorities. |
| /sbin     (System Binaries)     | Like the /bin directory, the /sbin contains binary executable. For system maintenance<br/>purposes, the Linux commands located in this directory are used typically by system
administrators. |
| /srv       (Service Data)       | Data for services provided by the system are located in /srv . For example if you are<br/>using the Apache HTTP server to serve a website, then you will probably save or
store your website's files in a directory under the /srv directory. |
| /tmp (Temporary Files)          | Temporary files created by system and users are located in /tmp . Note the the files in<br/>this directory are automatically deleted when the system is rebooted . |
| /usr           (User Programs)  | Applications and files used by users are located in /usr .   |
| /var      (Variable Data Files) | The writable counterpart to the /usr directory is the / var directory. Everything<br/>including log files that will be written to /usr (during normal operation) will be
automatically written to the /var directory .For example, Log files will be found in
/var/log. |

