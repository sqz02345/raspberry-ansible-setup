# Raspberry Pi Ansible Setup

This project allows you to configure Raspberry Pi devices from a macOS control node using Ansible.

## 🧰 Requirements

- Ansible (install via `brew install ansible`)
- SSH access to the Raspberry Pi

## 📦 Inventory

Edit `inventory.ini` with your Raspberry Pi IPs and users.

## ▶️ Run Playbook

```bash
ansible-playbook -i inventory.ini site.yml
```

## ✅ Included Roles

- `update`: Updates APT and upgrades packages
- `docker`: Installs Docker
