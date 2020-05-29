# All documents

## 0. Outline 

* (1) Installing nginx on ubuntu 

## 1. Installing nginx on ubuntu 
Ref: https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-18-04

```
$ sudo apt update
$ sudo apt install nginx
```

List firewall services 
```
$ sudo ufw app list
$ sudo ufw status
# Enable ufw 
$ sudo ufw enable
# Enable Nginx
$ sudo ufw allow 'Nginx HTTP'
```

Check nginx status 
```
$ systemctl status nginx
# Stop 
$ sudo systemctl stop nginx
# Start 
$ sudo systemctl start nginx
# Restart 
$ sudo systemctl restart nginx
# Enable 
$ sudo systemctl enable nginx
# Disable 
$ sudo systemctl disable nginx
```


