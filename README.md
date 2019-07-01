## Nsy

You can use init.sh to init your project.

```bash

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

