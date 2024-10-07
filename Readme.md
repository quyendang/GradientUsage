# Download Python
```bash
https://www.python.org/ftp/python/3.12.2/python-3.12.2-amd64.exe
```
# Install Python
![Python](https://i.imgur.com/dMWMSLX.png)

# Usage

Edit main.py, open main.py, replace MY_PROXY with your proxy:
```bash
MY_PROXY = "http://doremon1-zone-resi-region-us-session-session_id-sessTime-120:xxxxxxxx@na.pyproxy.io:16666"
```
Note! If your proxy:
```bash
http://doremon1-zone-resi-region-us-session-``ABHSJ9Sj``-sessTime-120:xxxxxxxx@na.pyproxy.io:16666
```

Change to:
```bash
http://doremon1-zone-resi-region-us-session-``session_id``-sessTime-120:xxxxxxxx@na.pyproxy.io:16666
```


## Run
```bash
pip install loguru
```

Requires version 0.1.1
```bash
pip install "websockets_proxy==0.1.1"
```

```bash
pip install async_timeout
```

```bash
pip install requests
```

```bash
python main.py <option> <threads>
```
option:
+ 1 : Use account from farms.txt, after farm list of node will saved to sessions.txt
+ 2 : Use account & node session from sessions.txt, When running, no new nodes will be created.
threads: Number of thread
For example:
```bash
# Run new node from farms.txt
python main.py 1 20
```

```bash
python main.py 2 20
```
