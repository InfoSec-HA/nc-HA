## nc-HA

nc-HA it's the real netcat tool, but the fetuar of nc-HA script is Wrote using python with some basic libraries.

## nc-HA fetuars

1. You can run the script with any os. 
2. Secure with antivireses.
3. an Esay control terminal.
4. Fast transfare.

------------------------------

# Run Script :

```
usage: nc_HA.py [-h] [-c] [-e EXECUTE] [-l] [-p PORT] [-t TARGET] [-u UPLOAD]

InfoSec-HA netcat tool with python

options:
  -h, --help                  show this help message and exit
  -c, --command               command shell
  -e EXECUTE, --execute       execute specified command
  -l, --listen                for listen
  -p PORT, --port PORT        specified port by default is 5555
  -t TARGET, --target TARGET  specified ip address
  -u UPLOAD, --upload UPLOAD  upload file
```

------------------------------

# An Example:

```
Example:
    nc-HA.py -t 192.168.1.108 -p 5555 -l -c # command shell
    nc-HA.py  -t 192.168.1.108 -p 5555 -l -u=mytest.txt # upload to file
    nc-HA.py  -t 192.168.1.108 -p 5555 -l -e=\ "cat/etc/passwd" # execute command
    echo 'ABC' | ./nc-HA.py  -t 192.168.1.108 -p 135 # echo text to server port 135
    nc-HA.py -t 192.168.1.108 -p 5555 # connect to server
```

------------------------------

# Devloper: Eng InfoSec-HA
# Contact With Twitter: (https://x.com/InfoS20215)
