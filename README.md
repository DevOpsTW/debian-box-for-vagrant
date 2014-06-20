Debian-Box-for-Vagrant
======================

The box of the minimal debian install for the Vagrant.

## Box description

* Box name : debian-7.5.0-minimal-x86_64-vmware_fusion-2014-06-18.box
* OS : Debian 7.5.0 x86_64
* Virtualization : VMware Fusion
* 4 CPU, 512MB RAM
* Installed packages : vim, curl, openssh-server, git-core
* Default user/password : vagrant/vagrant

## Prerequisites

* Vagrant (>= 1.6.3) (http://downloads.vagrantup.com)
* VMware Fusion (>= 6.0.3) (https://www.vmware.com/products/fusion/)
* Box (https://www.dropbox.com/s/4tc31qsh705wjni/debian-7.5.0-minimal-x86_64-vmware_fusion-2014-06-18.box)

## Getting Started

```bash
$ vagrant plugin install vagrant-vmware-fusion
$ vagrant plugin license vagrant-vmware-fusion license.lic
$ vagrant box add debian-7.5.0-minimal-x86_64-vmware_fusion-2014-06-18 https://www.dropbox.com/s/4tc31qsh705wjni/debian-7.5.0-minimal-x86_64-vmware_fusion-2014-06-18.box
$ vagrant init debian-7.5.0-minimal-x86_64-vmware_fusion-2014-06-18
$ vagrant up --provider=vmware_fusion
$ vagrant ssh
```
