# Ansible homelab

Ansible playbook for setting up my homelab machines. It is designed to run on a fresh install of Ubuntu and will install key packages, my Zsh config, Docker and Tailscale.

## Usage 

Update hosts file with the ip address of your target server.

Update `group_vars/all/var.yml` with your username on the target server.

```bash
ansible-playbook run.yml
```