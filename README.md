smbldap-tools
===

This role enables users to install and configure smbldap-tools with OpenLDAP client and Samba.

Requirements
------------

This role requires Ansible 2.0 or higher, and platform requirements are listed
in the metadata file.

Examples
--------

1) Install OpenLDAP, smbaldap-tools

	- hosts: all
	  roles:
	    - role: smbldap-tools

License
-------

BSD

Author Information
------------------

- Iori Mizutani

