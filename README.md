# Ansible Configuration

## Quick Start

```
sudo apt update && sudo apt upgrade -y
sudo apt install ansible

ansible pull -U https://github.com/AlexanderHott/config --ask-become-pass
```

## Local

```
ansible-playbook local.yml
```
