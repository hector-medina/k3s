# K3S.

## Installation.

### Install Debian.

We are using a Raspberry Pi so we are going to download the official image of Debian 2023.06.12	12 (Bookworm)	4	4 (8GB): https://raspi.debian.net/tested-images/

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
