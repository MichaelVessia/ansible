# Ansible Commands

## Basic run
`ansible-playbook local.yml --ask-become-pass`

## Run with a specific tag, become and vault passwords
`ansible-playbook -t tagname local.yml --ask-become-pass --ask-vault-pass`

## Post-run
`source ~/.profile` often helps when modifying paths
