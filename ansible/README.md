WordPress Vagrant Box - Ansible Playbook
========================================
Provisioning a remote instance directly via [Ansible][ANSIBLE].

Usage
-----
From the command line run:

```sh
ansible-playbook --user=$USER --ask-pass playbook.yml --extra-vars='ansible_python_interpreter=/usr/bin/python3'
```

[ANSIBLE]: https://www.ansible.com/
