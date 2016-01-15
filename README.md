# pydelhi-infra

[![Build Status](https://travis-ci.org/pydelhi/pydelhi-infra.svg?branch=master)](https://travis-ci.org/pydelhi/pydelhi-infra)

Configurations of all the servers and applications hosted under pydelhi.org.

## Getting Started

Clone this repository to your local machine:

```shell
git clone https://github.com/Anuj8826/wye_automation.git
cd wye_automation
```

Make sure you have [vagrant] and virtualbox installed, then run:

```shell
sudo pip install ansible
sudo ansible-galaxy install -r requirements.yml
vagrant up
```

You can login to the virtal machine with `vagrant ssh`. If you want to run any changes you have done in the ansible scripts, use `vargant provision` to run them against the virtual machine.

Use `vagrant destroy` to kill the virtual machine.


### Further Reading

1. https://docs.ansible.com/galaxy.html


[vagrant]: https://www.vagrantup.com/downloads.html

