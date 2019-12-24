Role Name
=========

Ansible HAProxy Role for IOTA

Requirements
------------

This role is used by Ansible playbooks such as [IRI-Playbook](https://github.com/nuriel77/iri-playbook), [GoShimmer-Playbook](https://github.com/nuriel77/goshimmer-playbook) and [Hornet-Playbook](https://github.com/nuriel77/hornet-playbook).

It installs HAProxy in Docker and provides a configuration specific for an IOTA node (IRI or Hornet).

Role Variables
--------------

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.) should
be mentioned here as well.

Dependencies
------------

[Ansible-Docker](https://github.com/nuriel77/ansible-docker)

Specific files, e.g. shared-files from [Hornet-Playbook](https://github.com/nuriel77/hornet-playbook/tree/master/roles/shared-files)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: haproxy, x: 42 }

License
-------

MIT

Author Information
------------------

[Nuriel Shem-Tov](https://github.com/nuriel77)
