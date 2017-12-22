# anisble-aws-roles
Ansible Roles for AWS Infrastructure Creation
To run the playbook, use this command
ansible-playbook -i inventory/hosts aws.yml -e@secret_vars/secret.yml --ask-vault-pass  
