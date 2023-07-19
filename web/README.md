## Ansible Playbooks

## Web

The Ansible playbook installs httpd, starts and enables it, and creates a simple website, all on it's own web node

- Install httpd
- Start and enable the httpd service
- Install a simple website provided on a repository server

`ansible-playbook -i /home/ansible/inventory /home/ansible/web.yml`