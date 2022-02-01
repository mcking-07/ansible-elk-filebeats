# ansible-elk-filebeats
Ansible playbook for deploying ELK Stack and Filebeats with SSL Certificate Security. Currently this has been tested on all versions from Ubuntu 16.04 LTS - Ubuntu 21.04 LTS.
###### This ansible-playbook can be used for ES 7.x only.
## Usage
- With `ansible.cfg`
> ansible-playbook ansible-elk.yml
- Without `ansible.cfg`
> ansible-playbook -i hosts ansible-elk.yml
