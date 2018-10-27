ansible-role-epel-release
=========================

A ansible role to install and/or configure epel-release.

Requirements
------------

* EL7

Role Variables
--------------

```yaml
epel_release_repo_epel_enabled: yes
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: kumarstack55.epel-release
```

License
-------

GPLv2

Author Information
------------------

@kumarstack55
