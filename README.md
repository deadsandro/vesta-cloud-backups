# vesta-cloud-backups

require https://github.com/abbat/ydcmd 

```bash
$ git clone https://github.com/abbat/ydcmd.git
$ sudo cp ydcmd/ydcmd.py /usr/local/bin/ydcmd
```

+ configure ydcmd
+ move folder in vestacp from /backup to /backup/daily (default backup)
+ create folder /backup/monthly
+ clone this repo and copy scripts to $VESTA/bin directory
+ add scripts to cron 