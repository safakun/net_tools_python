# Simple Net tools written in Python

```bash
virtualenv venv
source venv/bin/activate
```
### For email sniffer
```bash
pip install kamene
```

### To find a local host to listen
```bash
ifconfig 
```
post should be 192.168.*.*

sudo ./proxy.py 127.0.0.1 21 ftp.target.ca 21 True 