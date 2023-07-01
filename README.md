# K3S.

## Requirements.

In order to use this repository, you will need the following hardware:
- Raspberry Pi 4

## Installation.

### Install Ubuntu.

In order to install this image, the Raspberry Pi Imager will be used https://www.raspberrypi.com/software/

### Log as root.

````
sudo su -
````

### Instal extra modules.

````
sudo apt install linux-modules-extra-raspi && reboot
````

### Install K3S.

````
curl -sfL https://get.k3s.io | sh -
````
