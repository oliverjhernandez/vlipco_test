vlipco_monitor
=========

Deploys a basic monitoring script for HTTP App

Requirements
------------

No requirements whatsoever.

Role Variables
--------------

- monitor_root: Directory where the script resides
- user: User which runs the script
- host: VPN internal IP address to chech
- port: Port of the application to check
- endpoint: Endpoint of the url (if applicable)


Dependencies
------------

No dependencies :)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, user: "monitoruser" }

License
-------

BSD

Author Information
------------------

Oliver Hernández
