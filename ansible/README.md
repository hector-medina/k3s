# Ansible



### Log as root.

````
sudo su -
````

### Allow cgroups.

In order to enable memory groups in the Raspberry Pi, edit the `/boot/firmware/cmdline.txt` file by adding the following settings:

````
cgroup_enable=memory cgroup_memory=1
````

You will also need to `reboot` your system before the following step.

### Install extra modules.

````
sudo apt install linux-modules-extra-raspi && reboot
````

### Install K3S.

````
curl -sfL https://get.k3s.io | sh -
````
