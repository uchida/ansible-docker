uchida.docker
=============

ansible role to install docker CE, community edition

Role Variables
--------------

```
docker_ce_version: '*'
```

`docker_ce_version` is a variable to specify docker CE version, default is `*`, use available latest version.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: servers
  roles:
     - role: uchida.docker
```

License
-------

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed)

dedicated to public domain, no rights reserved.
