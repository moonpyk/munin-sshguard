munin-sshguard
==============

a munin plugin showing the number of hosts blocked by sshguard

## Installation:
```bash
apt-get install sshguard
cp plugin-conf.d/sshguard /etc/munin/plugin-conf.d/sshguard
cp plugins/sshguard /etc/munin/plugins/sshguard
service munin-node restart
```

## Known to work on:
* Ubuntu 12.04 (Precise Pangolin)
* Debian Wheezy on Raspberry Pi (Raspbian)
