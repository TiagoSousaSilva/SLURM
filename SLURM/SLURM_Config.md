#Installation/Configuration Controller
```
hostnamectl set-hostname controller

apt install slurm-wlm
```
(2 ways of creating slurm.conf)
```
cd /usr/share/doc/slurmctld/
chmod +r slurm-wlm-configurator.html
python3 -m http.server
#Use the webserver and press on slurm-wlm-configurator.html
#Adjust the fields and press submit
#Copy the text and creat a file named slurm.conf in the controller in /etc/slurm to put the text
```
OR 
```
cd /etc/slurm
nano slurm.conf ##Copy the slurm.conf into this file
nano cgroup.conf ##Copy the cgroup.conf into this file

nano slurmd.service ##

systemctl daemon-reload
systemctl start slurmd
systemctl status slurmd
```

#Client
```
hostnamectl set-hostname node1

apt install slurm-wlm

cd /etc/slurm

wget [Controller's Private IP]:8000/slurm.conf ##Edit this with the Client slurm.conf
wget [Controller's Private IP]:8000/cgroup.conf

systemctl daemon-reload
systemctl start slurmd
systemctl status slurmd
```

#Test:

nano slurmtest.sh

Insert:

```
#!/bin/sh
# Submit to a specifc node with a command e.g.
#   sbatch --nodelist=cn01 slurmtest.sh 
# Submit to a random node with a command e.g.
#   sbatch slurmtest.sh

#SBATCH --job-name=slurmtest

hostname
uptime
```
Execute:

sbatch slurmtest && squeue
