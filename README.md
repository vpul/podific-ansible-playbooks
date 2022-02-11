# podific-ansible-playbooks

Ansible Playbooks for Podific server orchestration

Instructions for running playbooks:

1. Use ssh-copy-id to copy ssh public keys to the server.
2. Execuete 'bootstrap.yml' playbook to create non-root user account.
3. Ensure 'vaultpass' file contains vault password.
4. Ensure '.env' file's path in the vars/site_vars.yml is correct.
5. Ensure 'api_uri' port in the vars/site_vars.yml matches with the one in .env file.
6. Execute 'site.yml' to orchestrate server.
7. Now you may use PM2 to deploy the code.
