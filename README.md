linode_managed
===============

Creates a user for user by Linode managed services, with passwordless sudo
access.

Example Playbook
----------------

    - hosts: servers
      roles:
         - linode_managed

Role Variables
--------------

 * linode_managed_username: linode

    Specify the username for the linode account.

 * linode_managed_ssh_pub_key: ssh-rsa AAAA....

    Override the SSH public key to add to the linode account.

Role Handlers
-------------

none.
