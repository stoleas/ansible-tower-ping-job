# Ansible Tower Ping Job

This Ansible playbook is used for running a playbook against the `api/v2/ping/` and `api/v2/config/` endpoint Ansible Tower endpoint to gather statistical data on the capacity, availability, and license usage of the Ansible Tower nodes.

# Requirements

This playbook requires the implementation of [Ansible Vault|http://docs.ansible.com/ansible/latest/user_guide/vault.html] to encrypt the API username and password that has access to the `api/v2/config/` endpoint.

## Variables

Variable Name         | Description
--- | ---
ansible_tower_cluster | This is the fqdn name for your tower cluster (the VIP)

## Author

Edward Quail (equail@redhat.com)