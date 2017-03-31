# Ansible eBot

Deploy an ebot with ansible

After getting the repo update the reference with

  git submodule update --recursive --remote

Create aan ansible_hosts file with the list of IP who need configuration

Run:

    ansible-playbook -i ansible_hosts site.yml

Profit