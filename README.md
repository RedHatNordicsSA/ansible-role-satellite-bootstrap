ansible-role-satellite-bootstrap
================================

Playbook installs
[Red Hat Satellite](https://www.redhat.com/en/technologies/management/satellite)
client tools and registers or unregisters VM to Satelite.

Requirements
------------

[Red Hat Satellite](https://www.redhat.com/en/technologies/management/satellite)

Role Variables
--------------

There is list of variables in defaults/main.yml which can be overridden in
vault or in Tower. You may need to modify them to use this role.

Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - include_role:
      name: ansible-role-satellite-bootstrap


License
-------

BSD

Author Information
------------------

[Red Hat](https://redhatnordicssa.github.io/)
