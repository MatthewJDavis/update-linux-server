# update-linux-server

Ansible role to update linux servers

Simple role that will update Debian or RedHat based linux systems.

Currently uses the ansible yum module so no Python3 support on host yet.

# TODO example use

To install use ansible-galaxy command:

```bash

ansible-galaxy install https://github.com/MatthewJDavis/update-linux-server.git

or use the requirements.yml file with ansible-galaxy

ansible-galaxy install -f requirements.yml
```
