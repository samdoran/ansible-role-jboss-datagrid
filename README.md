JBOSS Data Grid
=========
[![Galaxy](https://img.shields.io/badge/galaxy-samdoran.jboss--datagrid-blue.svg?style=flat)](https://galaxy.ansible.com/samdoran/jboss-datagrid)

Install JBoss Data Grid

Requirements
------------

Red Hat Subscription.

Role Variables
--------------

| Name              | Default Value       | Description          |
|-------------------|---------------------|----------------------|
| `` | `` |  |

Dependencies
------------

- `samdoran.redhat-subscription`
- `samdoran.java`

Example Playbook
----------------

    - hosts: jdg
      roles:
        - samdoran.java
        - samdoran.jboss-datagrid

License
-------

MIT
