# ubuntu-bionic64-desktop

## Overview

## Dependency

* Vagrant
* vagrant-disksize
* vagrant-vbguest

## Setup

### virtual machine setup

1. git clone
1. set up ssh key in playbook/roles/users/files/.ssh
1. modify keyboard type at playbook/roles/xubuntu/vars/main.yml
1. vagrant up
1. after setup vagrant halt
1. vagrant up again

### after first login

* setup ibus
* setup ulancher
* anyenv install --init
   after install *env please reboot virtual machine


## Usage

1. login virtual machine dev/password


## Licence
MIT License

## Authors
fitgogo


## References

https://qiita.com/hidekuro/items/81ae801b3cc5f72f0cc5

https://github.com/hidekuro/ansible-sandbox

https://galaxy.ansible.com/gantsign/visual-studio-code

https://galaxy.ansible.com/gantsign/atom

thanks, @hidekuro

