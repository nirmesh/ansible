# Vagrant Lab Environments

This repository contains lab environments which can be built using Vagrant and VMware Workstation Pro/Oracle VirtualBox.

Both Vagrant and VMware Workstation Pro/Oracle VirtualBox must be installed and configured before we can build these environments.

To bring up a VM or a set of VMs, change directory to respective directory and run following command.
```
vagrant up
```

**Note:** VMware Workstation Pro users need to update the 3rd octant of IP Address as per the IP range assigned to the NAT network adapter.
To find the valid range, open VMware Workstation Pro, go to Edit -> Virtual Network Editor. Check the IP range assigned to VMnet8 network.

![image](https://user-images.githubusercontent.com/18697093/178726667-77a9c303-e3c3-42f4-b5f5-032f4d9b52ed.png)


Currently available environments.

| Environment | IP Addresses |
| ----------- | ------------ |
| Ubuntu 20.4 | 192.168.*.11 |
| Ubuntu 18.4 | 192.168.*.12 |
| CentOS 7 | 192.168.*.13 |
| Rocky Linux 8 (Replacement for CentOS 8) | 192.168.*.14 |
| Ubuntu 22.04 | 192.168.*.15 |
| Ansible Lab | 192.168.*.[21-23] |
| Ansible Tower Lab (Coming soon) | 192.168.*.[31-33] |
| Puppet Lab (Coming soon) | 192.168.*.[41-43] |
| PE Lab (Coming soon) | 192.168.*.[51-53] |
| Telegraf, InfluxDB, Grafana | 192.168.*.[61-63] |
