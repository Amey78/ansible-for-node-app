# Assignment 1 - Ansible Inventory and Variables

I used Ansible to deploy a Node.js app on an AWS EC2 (Ubuntu) server.

# Files
- inventory.ini: EC2 server details
- playbook.yml: installs Node.js, clones the repo, starts the app

# Variables
repo_url, app_dir, node_version and app_file are set at the top of the playbook.
To change anything, edit just one line.

# Note
The given repo was not available, so I used my own: Amey78/node-app

# Run
ansible-playbook -i inventory.ini playbook.yml
