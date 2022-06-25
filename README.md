# VM-Commands

List of VM's running
```bash
VBoxManage list vms
```

Deleting Vm
```bash
VBoxManage unregistervm vm_id --delete
```

Check the packages which are installed for virtualbox
```bash
dpkg -l | grep virtualbox
```

Uninstall  packages for virtual box
```bash
sudo apt-get remove virtualbox* --purge
```
