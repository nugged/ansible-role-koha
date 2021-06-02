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
* ```koha_field_config``` - Path of custom elasticsearch field configuration file
* ```koha_index_mappings``` - Path of custom elasticsearch mappings configuration file
* ```koha_custom_index_mappings``` - Whether to use custom template file for elasticsearch index mappings
* ```koha_custom_index_config``` - Whether to use custom template file for elasticsearch index config
* ```koha_custom_field_config``` - Whether to use custom template file for elasticsearch field config
* ```koha_custom_z3950_pqf_properties``` - Whether to use custom template file for Z39.50 pqf properties
* ```koha_custom_z3950_attributes``` - Whether to use custom template file for Z39.50 attributes mappings
* ```koha_custom_z3950_config``` - Whether to use custom template config file for Z39.50
* ```koha_custom_oai_pmh``` - Whether to use custom template file for OAI-PMH settings
* ```koha_override_hourly_crons``` - Whether to override hourly cronjobs
* ```koha_override_daily_crons``` - Whether to override daily cronjobs
* ```koha_override_monthly_crons``` - Whether to override monthly cronjobs
* ```koha_override_koha_crons``` - Whether to override koha cronjobs

## License

MIT
