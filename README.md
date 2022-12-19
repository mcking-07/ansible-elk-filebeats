# ansible-elk-filebeats
Ansible playbook for deploying ELK Stack and Filebeats on Multiple Servers with SSL Certificate Security. Currently, this has been tested on all Ubuntu LTS versions from Ubuntu 16.04 LTS - Ubuntu 21.04 LTS.
#### This ansible-playbook can be used for ES 7.x only. 
Here, elasticsearch and kibana are deployed on server-1 while logstash and filebeats are deployed on server-2 which contain the log files. Also, logstash is configured to match the default nginx access log format.
## Usage
> ansible-playbook -i hosts ansible-elk.yml
