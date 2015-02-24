Ansible setup for my dev env.
===

### Prerequisites

+ Ubuntu 14.04 trusty 64bit

### Install ansible

```bash
$ sudo apt-get install python-pip

$ sudo pip install ansible
```

### Usage

```bash
$ ansible-playbook -i local site.yml --ask-sudo-pass
# step exec
$ ansible-playbook -i local site.yml --ask-sudo-pass --step
```
