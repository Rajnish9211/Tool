# Elasticsearch Ansible Role

This role automates the installation and configuration of Elasticsearch using Ansible.

## Features
- Installs Elasticsearch
- Configures Elasticsearch settings
- Manages service state
- Supports custom variables and templates

## Directory Structure
- `defaults/`: Default variables for the role
- `handlers/`: Handlers for service restart/reload
- `meta/`: Role metadata
- `tasks/`: Main tasks for installation and configuration
- `templates/`: Jinja2 templates for configuration files
- `vars/`: Additional variables

## Usage
Include this role in your playbook:

```yaml
- hosts: elasticsearch
  roles:
    - role: elasticsearch
```

Customize variables in your playbook or in `vars/main.yml` as needed.

## Example Inventory
See `inventory.ini` for sample host definitions.

<img width="1600" height="812" alt="Screenshot 2025-07-13 070131" src="https://github.com/user-attachments/assets/57a99525-88b5-4cf7-a9ed-208e85084293" />
<img width="1714" height="877" alt="Screenshot 2025-07-13 070140" src="https://github.com/user-attachments/assets/5f6453f8-606e-40e6-9e25-7113dfae5788" />

