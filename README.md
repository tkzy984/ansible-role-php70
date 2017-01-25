Role Name
=========

An Ansible role that installs PHP 7.0 with DTrace on FreeBSD

Dependencies
------------

- tkzy984.ports - fetch Ports collection

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: tkzy984.php70 }

License
-------

BSD
