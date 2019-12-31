vlipco_nodeapp
=========

Ansible role that deploys a simple Node App

Requirements
------------

You might need super user privileges depending on where you want to deploy the
app


Role Variables
--------------

- project_root_path: Where the app's located
- nodejs_version: Node.Js version number
- deploy_app_dir: Root directory for the app

Dependencies
------------

No dependencies :)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename }

License
-------

BSD

Author Information
------------------

Oliver Hernández
