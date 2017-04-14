ClamAV-daemon
=============

An Ansible role to install and configure [ClamAV](https://www.clamav.net/)
daemon, the virus and malware scanner.

Role Variables
--------------

See `defaults/main.yml`.

Example Playbook
----------------

    - hosts: servers
      roles:
         - mathieumd.clamav-daemon

License
-------

GPLv3
