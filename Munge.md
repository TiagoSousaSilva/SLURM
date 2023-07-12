#Confirguration (Should be done in every machine)
```
apt install munge libmunge2 libmunge-dev

chown -R munge: /etc/munge/ /var/log/munge/ /var/lib/munge/ /run/munge/
chmod 0700 /etc/munge/ /var/log/munge/ /var/lib/munge/
chmod 0755 /run/munge/
```
#Client Config

Controller:
```
cd etc/munge
python3 -m http.server
```
Nodes:
```
cd /etc/munge
rm munge.key
wget [Controller's Private IP]:8000/munge.key   ## This will download the munge.key from the controller which will provide the right key to the node
```

#Enable the munge.service
```
systemctl enable munge
systemctl start munge
```


#Check the Key
```
munge -n                    # Generate a credential on stdout
munge -n | unmunge          # Displays information about the MUNGE key  
munge -n | ssh somehost unmunge
```
