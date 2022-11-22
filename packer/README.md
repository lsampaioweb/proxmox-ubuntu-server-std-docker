# proxmox-ubuntu-22-04-server-std-docker
Packer project to create an Ubuntu template on Proxmox cloned from the server-standard and with Docker installed.

Run these commands on the computer that is running Packer:

```bash
  cd packer

  packer init config.pkr.hcl
  packer build -only="credencials.null.password" -var-file=project.pkrvars.hcl clone/.
  packer build -only="template.proxmox-clone.ubuntu" -var-file=project.pkrvars.hcl clone/.
  or 
  ./pipeline.sh
```

# Created by: 

1. Luciano Sampaio.
