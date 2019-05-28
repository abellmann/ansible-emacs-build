abellmann.emacs-build
=========
[![Build Status](https://travis-ci.org/abellmann/ansible-emacs-build.svg?branch=master)](https://travis-ci.org/abellmann/ansible-emacs-build)

A role to build [Emacs](https://www.gnu.org/software/emacs/) for X Windows

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
    - abellmann.ansible_emacs_build
```

License
-------

MIT

Author Information
------------------

Andreas Bellmann (https://github.com/abellmann)
