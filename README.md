# ansible-base
Basic Ansible project

### Trigger playbook for initial setup and qa environment with user root
ansible-playbook site.yml -i qa -u root

### Trigger playbook for update and production environment with user root
ansible-playbook update.yml -i production -u root
