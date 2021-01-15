Kibana
=========

    Install Kibana

Role Variables
--------------

    kibana_server_port:      5601
    kibana_es_port:          '{{ es_api_port }}'
    kibana_install:          true
    kibana_es_major_version: 7.x

Dependencies
------------

    elasticsearch

Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
         - { role: kibana }

License
-------

    MIT

Author Information
------------------

    Dmitrij Petrov
