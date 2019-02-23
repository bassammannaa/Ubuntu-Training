# Compress Commands

### **Commands**

~~~~
* Save command output to file
ls -al >> results
~~~~

```
* compress file
* first create file "file1"
touch file1

* use the following command to compress file1 (the new file will be file1.gz)
gzip file1

* use the following command to decompress file1 (the new file will be file1)
gunzip file1
```

```
* compress multiple files
* first create files (file1, file2, file3)
touch file1 file2 file3
ls

* compress files (file1, file2, file3) to myfiels
tar cvf myfiels file1 file2 file3

* decompress myfiels to (file1, file2, file3)
tar xvf myfiels
```

```
* Download & upgrade softwares using commands (apt = advance package tool)
* to update the download links for softwares
sudo apt-get update

* to upgrade the current softwares to be all installed softwares up-to-date
sudo apt-get upgrade

* dwonload softwares "gparted"
sudo apt-get install gparted


```

[Back](https://github.com/bassammannaa/Ubuntu-Training/blob/master/README.md)
