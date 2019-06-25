Role Name
=========

Install packages for Ubuntu and CentOS systems.  Both from repositories and manually downloaded files

Requirements
------------

A system to be configured

Role Variables
--------------

Taken from Ansible gathered facts

Dependencies
------------

N/A.

Helpful Links
-------------

* HFSPlus+
  * <https://pkgs.org/centos-7/elrepo-x86_64/kmod-hfsplus-0.0-1.el7.elrepo.x86_64.rpm.html>
  * <http://elrepo.org/linux/elrepo/el7/x86_64/RPMS/>
  * <http://superuser.com/questions/916225/mount-a-hfsplus-disk-with-read-write-permissions-in-linux>
  * <http://superuser.com/questions/84446/how-to-mount-a-hfs-partition-in-ubuntu-as-read-write>

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Matt DePorter
