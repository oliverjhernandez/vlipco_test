vlipco_ovpn
=========

Desploys an OpenVPN server and client

Requirements
------------

Root privileges to install packages (sudo)

Role Variables
--------------

- ca_file: Location of the certififcate authority file used by both the server
  and client
- cipher: CIpher used for encription
- server_crt_file: Location of the server's certificate file
- server_key_file: Location of the server's key file
- server_dh_file: Location of the server's DH file
- server_status_file: Location of the server's status log file
- client_cert_file: Location of the client's certificate file
- client_key_file: Location of the client's key file

Dependencies
------------

No dependencies :)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: vpnhost
      roles:
         - { role: vlipco_ovpn,  type: server }

License
-------

BSD

Author Information
------------------

Oliver Hernández
