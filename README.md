# Ansible Playbook: Remove File

This repository contains a simple Ansible setup to remove a specific file from target hosts. It includes a playbook, inventory, and configuration file.

## Files

- **remove_file.yml**  
  An Ansible playbook to delete the file `/path/to/your/file.txt` on all hosts defined in the inventory. The playbook runs with elevated privileges (`become: true`).

- **inventory.yaml**  
  Defines the target hosts where the playbook will be executed. Example:

  ```yaml
  all:
    hosts:
      example.com:
