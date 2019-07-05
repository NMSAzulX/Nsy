## Nsy

#### Environment  

&ensp;&ensp;&ensp;&ensp;You can build a remote develop environment according [this](https://github.com/NMSAzulX/Nsy/projects/2).  


#### Initialize Project  


&ensp;&ensp;&ensp;&ensp;You can use **init.sh** to initialize your project.

```Shell

# -php  means the version of the php you are using.
# -fp   means the port of the fastcgi
# -np   means the port of your nginx server

sh init -php 72 -fp 9001 -np 8080


# the next you will see the 'config'、'logs'、'start'、'stop' in your workspace.
# now let's start the server!

sh start


# and you can stop your server with 'stop'

sh stop

```  


#### Trace Log  

```Shell

# First of all. You should restart or reopen your terminal.  
# Maker sure the alias command work.


# trace fpm access log.

fpmaccess


# trace fpm error log.

fpmerror


# trace nginx access log

nginxaccess


# trace nginx error log.

nginxerror

```
Here is the result: 
![Trace Log](https://github.com/NMSAzulX/Nsy/blob/master/Image/TraceLog.png)
