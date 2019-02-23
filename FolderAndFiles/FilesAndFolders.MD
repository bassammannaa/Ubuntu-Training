# Work with Folders and Files

### **Commands**

~~~~
* Get cuurent path
PWD
~~~~

~~~~
* move up folder
CD ..
~~~~

~~~~
* move up to root /
CD /
~~~~

~~~~
* move to folder home (You can use TAB for auto complete)
CD home
~~~~

```
* move to specific path (You have to start with / )
CD /var/log
```

```
* Browse directory
ls
* Browse directory using full path
ls -a
* browse directory using full details of folder security
ls -al
```

```
* Create directory "folder1"
mkdir folder1

* check if folder1 is created or no ?
ls

* navigate to folder1
cd folder1

* create folder2 inside folder1
mkdir folder2

* delete folder2
rmdir folder2

* check if folder2 is deleted or no ?
ls

* create file1
touch file1

* remove file1
rm file1

* create folder2 again inside folder1
mkdir folder2

* navigate to folder2
cd folder2

* create file2 inside folder2
touch file2

* go out from folder2
cd ..

* browse directory
ls -all

* delete folder2 (you cannot use command rmdir because the folder is not empty)
rmdir -r folder2

```



```
* create originalfile1 then check if created or no
touch originalfile1
ls

* create new copy from originalfile1 and name it copyfile1
cp originalfile1 newcopyfile1
ls

* create new copy from copyfile1 and name it copyfile2
cp copyfile1 copyfile2
ls

* create new folder called myfiles
mkdir myfiles
ls

* move file newcopyfile1 to folder myfiles
mv newcopyfile1 myfiles/
ls

* move file newcopy2 to foder myfiles but change its name to xxxxx
mv newcopy2 myfiels/xxxx
ls
cd myfiles
ls

* rename file originalfile1 to yyyyy
mv originalfile1 yyyy
ls
```

```
* open new file (file1) using editor and save some words like (apple mango orange) 
* close the file and search for word "apple" using the following command
grep apple files 

* open another new file (file2) using editor and save some words like (apple dog cat) 
* close the file and use command "diff" to compare the contents between both files
diff file1 file2

```

[Back](https://github.com/bassammannaa/Ubuntu-Training/blob/master/README.md)


