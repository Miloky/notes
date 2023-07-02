Connect to Lightsail instance:

```bash
shh -i /[pem-file-name].pem [user-name]@[static-ip/ip-connect-to]
```

Start/restart/stop service:
```bash
systemctl start [service-name].service
systemctl restart [service-name].service
systemctl stop [service-name].service
systemctl status [service-name].service
```

Copy files to remote machine:
```bash
chown [username] [location]
scp -i ~/[filename].pem ~/[source-file-location] [username]@[ip]:[destination-location]
```

Logs:
```bash
journalctl -u [service-name].service -b
```

Other:
```bash
/var/www/wallet

/etc/systemd/system/wallet.service
```
