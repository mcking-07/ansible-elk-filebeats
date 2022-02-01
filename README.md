# ansible-elk-filebeats
Ansible playbook for deploying ELK Stack and Filebeats with SSL Certificate Security. Currently this has been tested on all versions from Ubuntu 16.04 LTS - Ubuntu 21.04 LTS.
#### This ansible-playbook can be used for ES 7.x only. 
#### Elasticsearch
Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the ELK-Stack. You can use Elasticsearch to store, search, and manage data for logs, metrics, a search backend, application monitoring, endpoint security, etc,.
#### Logstash
Logstash is a server-side data processing pipeline that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favorite "stash".

`In this ansible-playbook, Logstash matches the default nginx access.log format.`
#### Kibana
Kibana is your window into the Elastic Stack. Specifically, it's a browser-based analytics and search dashboard for Elasticsearch.
#### Filebeat
Filebeat is an open source file harvester, mostly used to fetch logs files and feed them into logstash.
## Usage
- With `ansible.cfg`
> ansible-playbook ansible-elk.yml
- Without `ansible.cfg`
> ansible-playbook -i hosts ansible-elk.yml
