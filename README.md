# Ansible up and running

## This is just following the book

## Setting the environment
- install ansible
- mkdir playbooks and inside start vagrant:
```
vagrant init ubuntu/trusty64
vagrant up
```

- ssh into vagrant:
```vagrant ssh```

- file hosts should be in playbooks directory and should contain the virtual machines
- ansible.cfg points to hosts, keys and remote_user
> Note: if there is a path to key in ansible.cfg, it should not be again in hosts, cos it caused problems

