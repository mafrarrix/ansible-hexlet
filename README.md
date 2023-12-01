# Ansible Playbooks

<p align="center">
<img src=https://tel4vn.edu.vn/uploads/2020/07/ANSIBLE-01-2048x1177.jpg>
</p>

### General Directory Structure

- **playbooks/**
  - **create_user.yml**: *Creates users with specified shells.*
  - **install_git.yml**: *Installs Git on the target servers.*
  - **setup_workspace.yml**: *Sets up the workspace directory.*
  - **main.yml**: *Main playbook that includes other playbooks.*
  - **role_main.yml**: *Example use case*
- **roles**: *The directory containing the roles used in the playbook.*
- **inventory.ini**: *The inventory file for defining the target hosts.*

### Description

This playbook sets up the development environment for users, including the installation and configuration of essential tools such as Git. It automates the process of provisioning and configuring Git on target machines, enabling users to effectively manage version control and collaborate on GitHub repositories.
    
### Usage

To execute the playbooks, use the following command:

Make sure to update the inventory file (`inventory.ini`) with your target hosts.

#### Example role playbook
[Video del 01-12-2023 13:14:31.webm](https://github.com/mafrarrix/ansible-hexlet/assets/84633068/c7ec8b9e-76af-46d8-9483-db8d274ee2b1)


#### License

This project is licensed under the [MIT License](LICENSE).
