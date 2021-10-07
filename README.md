andrewrothstein.thanos
=========
![Build Status](https://github.com/andrewrothstein/ansible-thanos/actions/workflows/build.yml/badge.svg)

Installs [Thanos](https://thanos.io/).

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
    - andrewrothstein.thanos
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
