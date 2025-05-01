# proxmox-ubuntu-server-std-docker
Project with Ansible scripts to create an Ubuntu template on Proxmox cloned from the server-standard and with Docker installed.

Run the command in the terminal:
```bash
  ansible-playbook template.yml -e "hostname=ubuntu-24-04-server-std-docker"
  ansible-playbook kvm_setup.yml -e "node=edge-pve-01 vm_name=ubuntu-24-04-server-std-docker"
```

#
### Created by:

1. Luciano Sampaio.
