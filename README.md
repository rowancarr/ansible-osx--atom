ansible-osx-atom
=========

Install Gitub Atom package on macOS 10.12

Requirements
------------

Requirements can be found in the metadata

Role Variables
--------------

```
osx_atom_host: https://github.com/atom/atom/releases/download
osx_atom_version: v1.15.0
osx_atom_name: atom-mac
```

Example Playbook
----------------


```
    - hosts: servers
      roles:
         - { role: ansible-osx-atom }
```

License
-------

MIT
