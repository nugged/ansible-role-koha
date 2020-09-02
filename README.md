# Koha

This Ansible role does a Debian package based Koha installation that
supports Elasticsearch as the search engine.

## Role variables

* ```koha_enable_plugins``` - Whether to enable plugin feature in Koha
* ```koha_elasticsearch_server``` - Hostname/IP of Elasticsearch server to use
* ```koha_plack_workers``` - Amount of plack process to spawn to handle requests
* ```koha_plack_max_requests``` - Amount of requests after the plack process is restarted
* ```koha_signing_key_id``` - PGP key used to verify packages
* ```koha_keyserver``` - PGP keyserver to use
* ```koha_package_repository``` - The Debian package repository to use
* ```koha_index_config``` - Path of custom elasticsearch index configuration file
* ```koha_index_mappings``` - Path of custom elasticsearch mappings configuration file

## License

MIT
