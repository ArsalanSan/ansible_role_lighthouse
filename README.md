Lighthouse
=========

This role can install Lighthouse on Centos 7

Role Variables
--------------

|vars|description|
|--------|-------------|
|lighthouse_repo|installation files|
|lighthouse_dir|installation directory|

Example Playbook
----------------
```
- name: Lighthouse | Install
  hosts: servers
  roles:
    - lighthouse
```

License
-------

MIT

Author Information
------------------

ArsalanSan
