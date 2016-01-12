=====================
Add User Ansible Role
=====================

:ABOUT: Add a user, a group and local-machine public key to remote authorized_keys

Vars
====

::

  {
    install_user: "<user>"
    install_group: "<group>"
    ssh_public_key: "{{ lookup('file', '<path/to/key.pub>') }}"
  }

