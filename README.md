# Ansible Repository for Multi-Environment Deployment

This repository contains Ansible playbooks and roles for managing the deployment of applications across different environments (development, staging, production).

## Getting Started

### Prerequisites

- Ansible installed on your local machine. [Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- Access to your target servers (development, staging, production) via SSH.

### Configuration

1. **Clone the repository:**
  
  ```git clone https://github.com/mouados-byte/ansiblerepo.git```

2. **Set up your inventory files:**

Define your hosts in the inventory/ directory.

3. **Configure Ansible settings:**

Modify the ansible.cfg file to suit your environment.

4. **Put ci.yml in your .github directory**

Copy the ./ci.yml to your .github directory
