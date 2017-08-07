# Project-6-Udacity

# Linux Server Configuration the 6th and final project


## IP address
```
13.58.150.79
```

### Server Link 
```
http://www.sherouk.tk
```

### Packeges Which was installed 

```
apache
postgresql
python 2.7
```
## 5. Update all currently installed packages

sudo apt-get update
sudo apt-get upgrade

## 6. Change the SSH port from 22 to 2200
1. Use `sudo vim /etc/ssh/sshd_config` and then change Port 22 to Port 2200 , save & quit.
2. Reload SSH using `sudo service ssh restart`

## 7. Configure the Uncomplicated Firewall (UFW)

