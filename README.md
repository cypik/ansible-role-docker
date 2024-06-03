Role Name
=========
# Ansible Role: Docker

A brief description of the role goes here.

Requirements
------------
- Ansible 2.9+
- Supported OS: Ubuntu, Debian, CentOS, RHEL

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
- `docker_users` : Specify the user for docker.
- `docker_compose_version` : Specify the docker version to install.
- `ansible_os_family` : Specify the ansible_os_family.
- [Add any other configurable variables]
-
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------
- [List any dependencies or other roles required by this role]
-
A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

```yaml
- hosts: cypik
  roles:
    - { role: docker, docker_version: "1.21.2" }

```

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------
This project is licensed under the MIT License - see the [LICENSE](https://github.com/cypik/ansible-role-docker/blob/master/LICENSE) file for details.
