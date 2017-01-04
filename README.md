Ansible role "gentoo.docker"
=========

Role for adding docker/docker-compose/docker-registry/docker-swarm.

Requirements
------------

Works only on gentoo distro.

Role Variables
--------------

```yaml
docker_packages_meta: []     # packages meta (use/keywords). See dependencies
                             # in meta/main.yml
docker_users: []     
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: gentoo.docker }

License
-------

BSD
