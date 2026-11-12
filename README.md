# Ansible repository for my personal use to manage homelab

In development/learning stage. 

## Userfull terminal commands:
```
ansible-playbook playbooks/tools/network-informations.yml --limit l340
ansible-galaxy install -r requirements.yml
```

## Target machines requirement packages:
```
apt install bridge-utils debootstrap openssh-server tcpdump vlan python3
```