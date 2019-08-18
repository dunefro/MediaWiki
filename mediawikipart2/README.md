Role Name
=========

It is a role used for installing the mediawiki in docker containers

Requirements
------------

The only requirement in the this role is that it should be deployed onto the machine already having docker yum repository.
  
Role Variables
--------------

No variable dependencies though few important variables already defined and must be used in the same way written after the playbook is executed.

mysql user - wiki_user
mysql database - mediawiki_db
mysql password - mediawiki

NOTE: The user is allowed granted privileges from every IP.


Dependencies
------------

No other dependencies except the managed host must be centos or rhel.
Example Playbook
----------------

The example is given in the README.md file in the parent directory.
License
-------

BSD

Author Information
------------------

Name - Vedant Pareek
email - pareekvedant99@gmail.com
