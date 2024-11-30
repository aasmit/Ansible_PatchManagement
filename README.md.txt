# Automated Linux Patch Management with Ansible

## Overview
This project automates Linux system updates using Ansible. It supports Ubuntu/Debian and CentOS/RHEL distributions.

## Features
- Automates package updates.
- Reboots systems if necessary.
- Logs patching outcomes on target machines.

## How to Use
1. Clone the repository.
2. Modify `inventory.yml` to include your target systems.
3. Run the playbook:
   ```bash
   ansible-playbook -i inventory.yml patch-management.yml
