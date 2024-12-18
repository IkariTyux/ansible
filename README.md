# This repo will not be usable until there is a v1 in the releases. Thanks

---

# Ansible

This repo contains ansible playbooks and python scripts that can manage VMs and Containers in a PVE instance starting from a blank installation.
The use of python makes it usable on every OS.

## What can be done
- Create/Delete VMs or CT
- Clone from template
- Start/Stop VM/CT (Force stop included)
- Sytsem Updates for VM/CT
- Update the Host
- Bulk create from CSV file

## Minimal Requirements
- Already installed proxmox-ve server (Version 7 or more)
- SSH access on the server
- Proxmoxer installed on the server (`pip install proxmoxer  --break-system-packages`)
- Python and Ansible installed on your machine
