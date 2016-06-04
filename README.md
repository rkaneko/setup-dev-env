Ansible setup for my dev env.
===

### Prerequisites

+ Ubuntu 14.04 trusty 64bit

### Install ansible

```bash
$ sudo apt-get install python-pip python-dev

$ sudo pip install ansible markupsafe
```

### Usage

```bash
$ ansible-playbook -i localhost site.yml --ask-become-pass
# step exec
$ ansible-playbook -i localhost site.yml --ask-become-pass --step
```

If u succeed setting up, start `zsh`.

```bash
$ zsh
```
