andrewrothstein.gosec
=========
![Build Status](https://github.com/andrewrothstein/ansible-gosec/actions/workflows/build.yml/badge.svg)

Installs [gosec](https://github.com/securego/gosec)

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
    - andrewrothstein.gosec
```

License
-------

MIT

Author Information
------------------

* Victor Michel <victormichel95@gmail.com>
* Andrew Rothstein <andrew.rothstein@gmail.com>
