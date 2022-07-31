# Ansible Commands

## Basic run
`ansible-playbook local.yml --ask-become-pass`

## Run with a specific tag, become and vault passwords
`ansible-playbook -t tagname local.yml --ask-become-pass --ask-vault-pass`

## Post-run
`source ~/.profile` often helps when modifying paths

## (De/En)crypting content with Ansible Vault
[docs](https://docs.ansible.com/ansible/latest/user_guide/vault.html#encrypting-files-with-ansible-vault)

`ansible-vault encrypt foo.yml`

Decrypt, edit, and re-encrypt with the following command:

`ansible-vault edit foo.yml`
