# Ansible Tower Ping Job

This Ansible playbook is used for running a playbook against the `api/v2/ping/` Asible Tower endpoint to gather statistical data on the capacity and availability of the Ansible Tower nodes.

## Variables

Variable Name         | Description
--- | ---
ansible_tower_cluster | This is the fqdn name for your tower cluster (the VIP)

## Author

Edward Quail (equail@redhat.com)