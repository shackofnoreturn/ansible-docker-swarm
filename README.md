# ansible-docker-swarm
*Automated provisioning and configuration of nodes into a `Docker Swarm`´`*

## What
**Docker Engine**
- Installing Docker


## How
**VSCode:**
- `CTRL` + `T`
- Choose playbook

**Terminal:**
- Alter variables at `vars/`
- Then run the playbook with your variable file
```bash
ansible-playbook -i inventory playbook-proxmox-container-create.yml -e @vars/proxmox-container.yml
```


## Todo
- Installing Docker
