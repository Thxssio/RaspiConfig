<h1 align="center"> 
  Fixed IP  
</h1>

***Wireless fixed IP***


```
netstat -nr
```

```
sudo service dhcpcd status
```
```
sudo nano /etc/dhcpcd.conf
```

```
interface wlan0
static ip_address=192.168.1.80/24
static routers=192.168.1.1
static domain_name_servers=192.168.1.1

```

```
sudo reboot
```
