# Ansible Playbooks: 

# Ansible Automation Project

This repository contains Ansible playbooks and roles for automating various tasks and configurations.

## 📂 Project Structure

The project is organized as follows:

ansible/
├── playbooks/ # Contains main playbooks
README.md

Example of Playbook:
## Files

- **remove_file.yml**  
  An Ansible playbook to delete the file `/path/to/your/file.txt` on all hosts defined in the inventory. The playbook runs with elevated privileges (`become: true`).

- **inventory.yaml**  
  Defines the target hosts where the playbook will be executed. Example:

  ```yaml
  all:
    hosts:
      example.com:
