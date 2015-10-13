# Vagrant Setup for GeoNode on Ubuntu 12.04

## Setup Vagrant

#### 1. Install VirtualBox (https://www.virtualbox.org/)
#### 2. Install Vagrant (https://docs.vagrantup.com/v2/installation/)
#### 3. Start and Provision Vagrant machine 
* `cd vagrant`
* `vagrant up`
* `vagrant provision`

## Create Admin User
```
vagrant ssh
geonode createsuperuser
sudo geonode-updateip 127.0.0.1:8001
```
