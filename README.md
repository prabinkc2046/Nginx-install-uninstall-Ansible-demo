# Ansible Playbook: Install and Uninstall Nginx on Linode Server

This repository contains an Ansible playbook to automate the process of installing and uninstalling Nginx on a remote Linode server. Ansible is a powerful automation tool that simplifies server management and configuration.

## Prerequisites

- A Linode server instance
- Ansible installed on your local machine
- Passwordless SSH access from your local machine to the Linode server

## Usage

Run the playbook to install Nginx:

```bash
ansible-playbook -i inventory.ini install_nginx.yml
```

This will install Nginx on your Linode server.

To uninstall Nginx from your Linode server, run the playbook:

```bash
ansible-playbook -i inventory.ini uninstall_nginx.yml
```

# License
This project is licensed under the MIT License.




