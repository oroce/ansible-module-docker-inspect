[WIP] Ansible Docker Inspect Module
====

This is an ansible module to inspect docker containers.

## Usage

Copy the the module as mentioned in the [Ansible documentation](http://docs.ansible.com/developing_modules.html).

In playbook:
~~~yaml
- name: find out port mapping
  docker_inspect:
	name=ubuntu
	tag=latest
  register: inspect_ubuntu
~~~
