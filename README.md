# AUTOMATED DEPLOYMENT

This repository contains the Ansible playbook and configuration for deploying and managing the AIHomework-Prod application. The playbook sets up the application, installs necessary dependencies, and configures services on the target machine.

## Requirements

- Ubuntu server
- Ansible installed
- SSH access to the server

## Setup Instructions

### 1. Clone the Repository
```bash
    git clone https://github.com/Afeez-AA/hng-project-ansible.git
```
### 2. From the cloned directory run the ansible playbook
```bash
    cd hng-project-ansible
    ansible-playbook main.yaml -b -i <<invetory file--optional>>
```
### 3. Confirm deployment
 This can be done by pasting the target server ip on a broswer, the expected output should be an `hello world` displayed, then verify each api routes.

 #### NB: After grading all variables will be encrypted using ansible vault
