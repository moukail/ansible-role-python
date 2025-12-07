Ansible Role Python
=========

Example Requirements
--------------------

```yml
---
roles:
  - name: ansible-role-python
    src: git+https://github.com/moukail/ansible-role-python.git
    version: main

```

Example Playbook
----------------

```yml
---
- name: Install Python
  hosts: all
  become: true

  vars:
    python_version: "3.14.0"

  roles:
    - ansible-role-python

```
