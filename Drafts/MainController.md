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
   47  cd /usr/share/doc/slurmctld/
   48  ls -l
   49  python3 -m http.server
   50  cd /lib/systemd/system
   51  nano slurmctld.service 
   52  systemctl restart slurmctld.service 
   53  systemctl daemon-reload
   54  systemctl restart slurmctld.service
   55  systemctl status slurmctld.service
   56  nano slurmctld.service 
   57  cd /etc/slurm
   58  ls -l
   59  nano slurm.conf 
   60  systemctl restart slurmctld.service
   61  nano slurm.conf 
   62  systemctl restart slurmctld.service
   63  systemctl status slurmctld.service
   64  nano slurm.conf 
   65  munge -n
   66  cd /etc/munge
   67  ls -l
   68  python3 -m http.server
   69  chown -R munge: /etc/munge/ /var/log/munge/ /var/lib/munge/ /run/munge/
   70  chmod 0700 /etc/munge/ /var/log/munge/ /var/lib/munge/
   71  chmod 0755 /run/munge/
   72  systemctl restart munge
   73  systemctl status munge
   74  munge -n
   75  systemctl restart slurmctld.service
   76  systemctl status slurmctld.service
   77  ls -l
   78  cd /etc/slurm
   79  ls -l
   80  nano slurm.conf 
   81  slurmd -C
   82  nano slurm.conf 
   83  systemctl restart slurmctld.service
   84  systemctl status slurmctld.service
   85  sinfo
   86  srun -N3 -l /bin/hostname
   87  cd /etc/slurm
   88  mkdir cgroup.conf
   89  rm -f cgroup.conf
   90  rm -R cgroup.conf
   91  nano cgroup.conf
   92  systemctl status slurmctld
   93  apt install munge libmunge2 libmunge-dev
   94  cd /etc/munge/
   95  ls -l
   96  python3 -m http.server
   97  ls -l
   98  systemctl enable munge
   99  systemctl start munge
  100  munge -n | unmunge
  101  cd /etc/slurm
  102  ls -l
  103  nano slurm.conf 
  104  systemctl restart slurmctld
  105  systemctl status slurmctld
  106  nano slurm.conf 
  107  cd /run
  108  ls -l
  109  cd /etc/slurm
  110  ls -l
  111  python3 -m http.server
  112  sinfo
  113  systemctl restart slurmctld
  114  systemctl status slurmctld
  115  nano slurm.conf 
  116  systemctl restart slurmctld
  117  systemctl status slurmctld
  118  systemctl restart slurmctld
  119  systemctl status slurmctld
  120  sinfo
  121  systemctl status slurmctld
  122  nano slurm.conf 
  123  systemctl restart slurmctld
  124  systemctl status slurmctld
  125  sinfo
  126  srun -N2 -l /bin/hostname
  127  srun -N3 -l /bin/hostname
  128  nano slurmtest.sh
  129  sbatch slurmtest.sh && squeue 
  130  history
  131  nano /etc/iptables/rules.v4
  132  exit
  133  history
