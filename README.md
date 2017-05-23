[![CircleCI](https://circleci.com/gh/fouadsemaan/ansible-package-installer.svg?style=svg)](https://circleci.com/gh/fouadsemaan/ansible-package-installer)
fouadsemaan.package-installer
=========

Installs packages specified at runtime.

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

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
Fouad Semaan <semaanfouad@gmail.com>

