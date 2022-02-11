# podific-ansible-playbooks

Ansible Playbooks for Podific server orchestration

Instructions for running playbooks:

1. Use ssh-copy-id to copy ssh public keys to the server.
2. Execuete 'bootstrap.yml' playbook to create non-root user account.
3. Ensure 'vaultpass' file contains vault password.
4. Ensure '.env' file's path in the vars/site_vars.yml is correct.
5. Execute 'site.yml' to orchestrate server.
6. Now you may use PM2 to deploy the code.
