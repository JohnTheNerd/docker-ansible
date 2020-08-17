# docker-ansible

An ansible playbook that installs Docker Community Edition and docker-compose. It also enables docker without sudo for the specified user (username must be specified under [external_vars.yml](external_vars.yml)). 

To use it, create an inventory file that has all of the hosts you need in the `docker` group (an example file can be found [here](inventory.ini)), and just run `ansible-playbook site.yml` - yes, that's really it!
