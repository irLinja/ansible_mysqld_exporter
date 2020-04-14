mysqld_exporter
=========

this role will install prometheus mysqld_exporter as a service on your servers supports any systemd distrubution.

Requirements
------------

--

Role Variables
--------------

- prometheus.config.mysqld.version: 0.12.1
- prometheus.config.mysqld.listen: will automaticaly set to fist private network ip address
- prometheus.config.mysqld.port: 9104
- prometheus.config.mysqld.path: /metrics
- prometheus.config.mysqld.user
- prometheus.config.mysqld.pass


Dependencies
------------

--

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - mysqld_exporter

License
-------

GPL-v3

Author Information
------------------

Arash Haghighat
