# Ansible Role: Elasticsearch ELK stack

**This role is for Debian based boxes only.**

Setup [Elasticsearch ELK Stack](http://www.elasticsearch.org/overview/) on Debian/Ubuntu linux servers.
New [Kibana (v4.4)](https://github.com/elasticsearch/kibana) is installed by this role.

Installs
- nginx
- monit
- supervisor
- Elasticsearch
- Kibana
- Logstash

I would like to remove monit, nginx and supervisor from this role, as they should be taken care
of by other roles. In fact this role could be split into 3 also, but for now, this is how it is.

## License
MIT

## Author Information
This role was originally created in 2014 by [Bakhti Aripov](http://bakhti.github.io/).
I am editing it so that it only contains Debian relevant code in order to simplify.
