# docker-ansible

An ansible playbook that installs Docker Community Edition and docker-compose. It also enables docker without sudo for the specified user. 

To use it, create an inventory file that has all of the hosts you need (groups don't matter, you'll get Docker installed on all hosts defined) and just run `ansible-playbook site.yml` - yes, that's really it!
