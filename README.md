# xtreamui
iptv panel with xtream ui

ubantu version 18.04 and 20.04 for xui.one


```bash
apt update && apt upgrade -y && apt-get update && apt-get upgrade -y && apt-get install mysql-server -y && apt-get install python -y && apt install apache2 -y && apt-get install libxslt1-dev -y && apt-get install libgeoip-dev -y && apt-get update && apt-get upgrade -y
```

```bash
sudo python install.py
```


$ sudo apt update
$ sudo apt upgrade

- To install openssh-server package, run:
$ sudo apt install openssh-server
- Once installed, the SSH service should be started automatically. If necessary, you can start (or stop, restart) the service manually via command:
$ sudo service ssh start
- Verify that ssh service running
$ sudo systemctl status ssh

- Configure firewall and open port 22
Before enabling the UFW firewall we need to add a rule which will allow incoming SSH connections. If you’re connecting to your server from a remote location, which is almost always the case and you enable the UFW firewall before explicitly allow incoming SSH connections you will no longer be able to connect to your Ubuntu server.
To configure your UFW firewall to allow incoming SSH connections, type the following command:

$ sudo ufw allow ssh



- Now we can enable UFW firewall by typing:
$ sudo ufw enable



- You can check the status of UFW with the following command:
$ sudo ufw status
