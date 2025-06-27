# Ansible Setup

## Requirements

```shell
# install ansible
sudo apt install ansible -y

# install ansible community plugins
ansible-galaxy collection install community.general
```

## Running

```shell
ansible-playbook -t system local.yaml --ask-become-pass
```
