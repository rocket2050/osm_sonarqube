Role Name
=========

Installing Sonarqube in RHEL/CentOS

Requirements
------------
For Sonarqube we need below package
java
mysql

Role Variables
--------------
I used below mention variables in my role

mysql_root_pass: XXXXX
dbname: XXX
dbuserpassword: XXXX
dbusername: XXX

in vars/main.yml u can change the value

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sonarqube }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
