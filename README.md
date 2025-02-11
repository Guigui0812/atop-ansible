Atop Role
=========

This role installs and configures the atop monitoring tool.

Requirements
------------

- [Ansible](https://www.ansible.com/) - Ansible must be installed to execute the playbook.

Role Variables
--------------

| Variable | Description | Default |
|----------|-------------|---------|
| `atop_interval` | The interval in seconds between each sample | `600` |

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - atop
```

License
-------

BSD
