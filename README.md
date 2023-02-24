![Ansible Lint](https://github.com/johanneskastl/ansible-role-put_hostname_into_index_html/workflows/Ansible%20Lint/badge.svg)

put_hostname_into_index_html
=========

Puts the hostname into a index.html (used by apache or nginx)

Requirements
------------

None.

Role Variables
--------------

`path_to_index_html`: (Required) Path to the file where the hostname should be put into.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: 'johanneskastl.put_hostname_into_index_html'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
