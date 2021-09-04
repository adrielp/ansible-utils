# Ansible Utilties Repository
This repository hosts various Ansible playbooks that I use as utility
helpers for configuring various aspects of my system.

# How to run a play
1. Install Ansible
```
# install with brew
brew install ansible

# install with yum
yum install -y ansible

# install with dnf
dnf install -y ansible
```
2. Run the play
```
ansible-playbook setup_dotfiles.yaml
```
