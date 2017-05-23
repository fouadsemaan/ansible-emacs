fouadsemaan.package-installer
=========

Installs packages specified at runtime.

Example to install vim and tree:

---
- hosts: all
  roles:
    - role: fouadsemaan.package-installer 
      pkgs:
        - vim
        - tree

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - role: fouadsemaan.package-installer 
      pkgs:
        - vim
        - tree
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
Fouad Semaan <semaanfouad@gmail.com>
