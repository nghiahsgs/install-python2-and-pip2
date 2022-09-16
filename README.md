# install-python2-and-pip2
install python2 and pip2

```
sudo apt update
sudo apt install python2
python2 -v
```


```
sudo apt update
curl https://bootstrap.pypa.io/pip/2.7/get-pip.py --output get-pip.py # Fetch get-pip.py for python 2.7 
python2 get-pip.py
```

restart the terminal
```
pip --version
```


install virtualenv
```
pip2 install virtualenv
```

```
which python2
-> /usr/bin/python2
```


create new venv
```
virtualenv -p /usr/bin/python2 isoEnv
```

activate venv
```
source isoEnv/bin/activate
```

deactivate venv
```
deactivate
```
