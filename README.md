# CreatProxyWithBBRPlus
Vultr CentOS 8 Creat Proxy With BBR Scripts

````
#!/bin/sh

wget -N --no-check-certificate "https://raw.githubusercontent.com/TrLOX/CreatProxyWithBBR/main/run.sh" && chmod +x run.sh && ./run.sh
sudo /usr/bin/htpasswd -b -c /etc/squid/passwd USERNAME_HERE PASSWORD_HERE
sudo systemctl reload squid
````
Proxy ip:3128:USERNAME_HERE:PASSWORD_HERE

## Debian

````
#!/bin/sh

wget -N --no-check-certificate "https://raw.githubusercontent.com/TrLOX/CreatProxyWithBBR/main/Debian/run.sh" && chmod +x run.sh && ./run.sh
sudo /usr/bin/htpasswd -b -c /etc/squid/passwd USERNAME_HERE PASSWORD_HERE
sudo systemctl reload squid
````
