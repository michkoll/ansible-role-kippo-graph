Ansible-Role: Kippo Graph
=========

Ansible role for installing [Kippo-Graph](https://github.com/ikoniaris/kippo-graph).

Automatic installation of php and apache2 included.

Requirements
------------

You need a running and configured MySQL database server.

Role Variables
--------------

Short description of role variables and default values:

```yaml
kg_cwd: "/var/www/html/kippo-graph"
```
Apache directory for Kippo-Graph.

Dependencies
------------

Ansible role [Cowrie](https://github.com/michkoll/ansible-role-cowrie)

The dependency will be eliminated in later versions for installing cowrie and kippo-graph independent.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: kippo-graph
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

&copy; 2018
Written by [Michael Koll](https://github.com/michkoll)
