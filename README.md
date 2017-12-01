Role Name
=========

A simple role to install and configure elasticsearch.

Requirements
------------

No Special requirements.

Role Variables
--------------

* ELASTICSEARCH_VERSION: The version of elasticsearch to install (default is 5.6.2)
* ELASTICSEARCH_CLUSTER_NAME: The name of cluster to use (default is elastic_cluster)
* ELASTICSEARCH_NODE_NAME: The name of the elasticsearch node to use (default is node_1)
* ELASTICSEARCH_HOST: The bind IP address for elasticsearch node (default is 127.0.0.1)
* ELASTICSEARCH_PORT: The bind port for elasticsearch node (default is 9200)

Dependencies
------------

* mohsenSy.java: JAVA_VERSION: 8

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: mohsenSy.elasticsearch }

License
-------

BSD

Author Information
------------------

If you have any question please contact me on

[twitter](https://twitter.com/mouhsen_ibrahim)

[linkedin](https://linkedin.com/in/mohsen-ibrahim-670b13112/)

email mohsen47@hotmail.co.uk
