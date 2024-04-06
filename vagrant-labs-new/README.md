# Vagrant Lab Environments

This repository contains lab environments which can be built using Vagrant and VMware Workstation Pro/Oracle VirtualBox.

Both Vagrant and VMware Workstation Pro/Oracle VirtualBox must be installed and configured before we can build these environments.

To bring up a VM or a set of VMs, change directory to respective directory and run following command.
```
vagrant up
```

# to connect from vscode make sure u install ssh extension else it wont show up under remote explorer
# install pip and ansible
```
sudo apt install python3-pip
sudo apt-get install ansible
```
# install ansible it will get installed in /home/vagrant/.local/bin

```
python3 -m pip install ansible-core
pip3 install ansible
vi ~/.bashrc
add this line export PATH="$PATH:/home/vagrant/.local/bin"
```

