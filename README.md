uchida.docker
=============

[![Ansible Role](https://img.shields.io/ansible/role/20899.svg?maxAge=2592000)](https://galaxy.ansible.com/uchida/docker/)
![Version](https://img.shields.io/github/tag/uchida/ansible-role-docker.svg)
[![License](https://img.shields.io/github/license/uchida/ansible-role-docker.svg?maxAge=2592000)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)
[![Travis](https://img.shields.io/travis/uchida/ansible-role-docker.svg)](https://travis-ci.org/uchida/ansible-role-docker)

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
