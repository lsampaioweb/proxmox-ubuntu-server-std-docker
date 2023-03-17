# proxmox-ubuntu-22-04-server-std-docker
Project with Ansible scripts to create an Ubuntu template on Proxmox cloned from the server-standard and with Docker installed.

Run the command in the terminal:
```bash  
  ansible-playbook template.yml -e "hostname=ubuntu-22-04-server-std-docker"
  ansible-playbook kvm_setup.yml -e "node=kvm-07 vm_id=903 hotplug=disk,network,cpu storage_pool=Ceph_Silver"
```

# Created by: 

1. Luciano Sampaio.
