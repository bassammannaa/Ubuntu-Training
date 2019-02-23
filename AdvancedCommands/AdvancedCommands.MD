# Advanced Commands

### **Commands**

```
* Nano editor

* install nano
sudo apt-get install nano

* open file using nano
nano path

* example:
nano /etc/group
```

~~~~
* Services

* Get list of service status
service --status-all

* stop service
service servicename stop

* start service
service servicename start

* restart service
service servicename restart

* force restart service
service servicename force-reload

* get service status
service servicename status

~~~~

```
* Applications Installations

* decompress deb files
sudo dpkg -i /path/to/debfile

* Install deb files
sudo apt-get install -f .
```

```
* Network commands
* To get your network card details
ifconfig
ifconfig -a

* To get PC IP details
ip addr show

* To get network state
sudo netstat
sudo netstat -ntlp
sudo netstat -ntlp |grep LISTEN
sudo netstat -ntlp |grep 5432
sudo netstat |grep 5432

* to ger current process source & destination & port
netstat -plnt
```

```
* OS
* get list of all process
ps aux

* kill process
kill processid

```



[Back](https://github.com/bassammannaa/Ubuntu-Training/blob/master/README.md)
