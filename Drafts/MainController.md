```
    1  su -
    2  sudo apt update
    3  sudo apt upgrade
    4  iptables -t nat -A POSTROUTING -o eth1 -j MASQUERADE
    5  sudo iptables -t nat -A POSTROUTING -o eth1 -j MASQUERADE
    6  sudo apt install iptables
    7  cd /etc/iptables/
    8  cd /etc/
    9  ls -l
   10  sudo nano /etc/iptables/rules.v
   11  sudo nano /etc/iptables/rules.v4
   12  iptables -t nat -A POSTROUTING -o eth1 -j MASQUERADE
   13  sudo iptables -t nat -A POSTROUTING -o eth1 -j MASQUERADE
   14  sudo systemctl start iptables
   15  sudo apt install iptables
   16  sudo apt-get install iptables
   17  exit
   18  sudo iptables -L -v
   19  sudo iptables -L
   20  sudo iptables -S
   21  sudo iptables -t nat -A POSTROUTING -o eth1 -j MASQUERADE
   22  netfilter-persistent reload
   23  iptables -t nat -A POSTROUTING -o eth1 -j MASQUERADE
   24  sudo apt install netfilter-persistent
   25  netfilter-persistent reload
   26  sudo netfilter-persistent reload
   27  sudo iptables -S
   28  sudo iptables -L
   29  sudo su
   30  sudo apt install slurm-wlm
   31  dpkg -L slurmctld
   32  cd /usr/share/doc/slurmctld/
   33  su
   34  su -
   35  history
   36  sudo su
   37  history
```
```
    1  netfilter-persistent save
    2  apt install iptables-persistent
    3  netfilter-persistent save
    4  nano /etc/iptables/rules.v4
    5  netfilter-persistent reload
    6  ip a
    7  nano /etc/iptables/rules.v4
    8  netfilter-persistent save
    9  sysctl -p
   10  nano /etc/syctl.conf
   11  cd /etc
   12  nano sysctl.conf 
   13  sysctl -+
   14  sysctl -p
   15  ip a
   16  nano /etc/iptables/rules.v4
   17  netfilter-persistent reload
   18  nano /etc/iptables/rules.v4
   19  netfilter-persistent svae
   20  netfilter-persistent save
   21  nano /etc/iptables/rules.v4
   22  python3 -m http.server
   23  chmod +r slurm-wlm-configurator.html
   24  python3 -m http.server
   25  slurmd -C 
   26  cd /etc/slurm/
   27  ls -l
   28  nano slurm.conf
   29  systemctl sudo apt-get install munge
   30  cd /etc/munge
   31  ls -l
   32  chown -R munge: /etc/munge/ /var/log/munge/ /var/lib/munge/ /run/munge/
   33  chmod 0700 /etc/munge/ /var/log/munge/ /var/lib/munge/ /run/munge/
   34  cexec chown -R munge: /etc/munge/ /var/log/munge/ /var/lib/munge/ /run/munge/
   35  chown -R munge: /etc/munge/ /var/log/munge/ /var/lib/munge/ /run/munge/
   36  chmod 0700 /etc/munge/ /var/log/munge/ /var/lib/munge/ /run/munge/
   37  systemctl enable munge
   38  systemctl start munge
   39  systemctl status munge
   40  munge -n | unmunge
   41  systemctl start slurmd slurmctld 
   42  systemctl status slurmd slurmctld 
   43  systemctl start slurmd slurmctld 
   44  systemctl status slurmd slurmctld 
   45  systemctl restart slurmd slurmctld 
   46  tail -f /var/log/syslog 
   47  cd /etc/slurm
   48  mkdir cgroup.conf
   49  rm -f cgroup.conf
   50  rm -R cgroup.conf
   51  nano cgroup.conf
   52  systemctl status slurmctld
   53  apt install munge libmunge2 libmunge-dev
   54  cd /etc/munge/
   55  ls -l
   56  python3 -m http.server
   57  ls -l
   58  systemctl enable munge
   59  systemctl start munge
   60  munge -n | unmunge
   61  cd /etc/slurm
   62  ls -l
   63  nano slurm.conf 
   64  systemctl restart slurmctld
   65  systemctl status slurmctld
   66  nano slurm.conf 
   67  cd /run
   68  ls -l
   69  cd /etc/slurm
   70  ls -l
   71  python3 -m http.server
   72  sinfo
   73  systemctl restart slurmctld
   74  systemctl status slurmctld
   75  nano slurm.conf 
   76  systemctl restart slurmctld
   77  systemctl status slurmctld
   78  systemctl restart slurmctld
   79  systemctl status slurmctld
   80  sinfo
   81  systemctl status slurmctld
   82  nano slurm.conf 
   83  systemctl restart slurmctld
   84  systemctl status slurmctld
   85  sinfo
   86  srun -N2 -l /bin/hostname
   87  srun -N3 -l /bin/hostname
   88  nano slurmtest.sh
   89  sbatch slurmtest.sh && squeue 
   90  history