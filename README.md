# Carls Linux Ansible Playbook

## Bootstrap
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/carlallen/ansible-mac/main/bootstrap.sh)"`


## Install Requirements
`ansible-galaxy install -r requirements.yml`

## Run Ansible
`ansible-playbook main.yml --ask-become-pass`
