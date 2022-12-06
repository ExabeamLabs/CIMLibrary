zeek
====

Expression
----------

product = zeek

Fields
------

| Field         | Core     | Detection | Informational |
| ------------- | -------- | --------- | ------------- |
| src_ip        | &#10003; |           |               |
| protocol      |          | &#10003;  |               |
| connection_id |          |           | &#10003;      |
| dest_ip       | &#10003; |           |               |

Activity Types
--------------

| Activity Type           | Field                        | Status  | Core     | Detection | Informational |
| ----------------------- | ---------------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger           | src_ip                       | Legacy  | &#10003; | &#10003;  |               |
|                         | src_port                     | Legacy  |          |           | &#10003;      |
|                         | protocol                     | Legacy  |          | &#10003;  |               |
|                         | dest_ip                      | Legacy  | &#10003; | &#10003;  |               |
|                         | src_host                     | Legacy  | &#10003; | &#10003;  |               |
|                         | dest_port                    | Legacy  |          | &#10003;  |               |
| dhcp-session            | duration                     |         |          | &#10003;  |               |
|                         | src_mac                      |         |          |           | &#10003;      |
|                         | dhcp_type                    |         |          | &#10003;  |               |
|                         | lease_time                   |         |          | &#10003;  |               |
|                         | domain                       |         |          | &#10003;  |               |
|                         | dest_host                    |         |          | &#10003;  |               |
|                         | session_id                   |         |          |           | &#10003;      |
|                         | user_uids                    |         |          |           | &#10003;      |
|                         | trans_id                     |         |          |           | &#10003;      |
|                         | user                         | Legacy  | &#10003; |           |               |
| dns-request             | query_id                     |         |          |           | &#10003;      |
| dns-response            | AA                           |         |          |           | &#10003;      |
|                         | TTLs                         |         |          |           | &#10003;      |
|                         | qclass_name                  |         |          |           | &#10003;      |
|                         | RD                           |         |          |           | &#10003;      |
|                         | rtt                          |         |          |           | &#10003;      |
|                         | trans_id                     |         |          |           | &#10003;      |
|                         | Z                            |         |          |           | &#10003;      |
|                         | qclass                       |         |          |           | &#10003;      |
|                         | user_uid                     |         |          |           | &#10003;      |
|                         | TC                           |         |          |           | &#10003;      |
|                         | RA                           |         |          |           | &#10003;      |
| email-receive           | rcptto                       | Default |          |           | &#10003;      |
|                         | cc                           | Default |          |           | &#10003;      |
|                         | session_id                   | Default |          |           | &#10003;      |
|                         | mailfrom                     | Default |          |           | &#10003;      |
|                         | message_id                   | Default |          |           | &#10003;      |
|                         | in_reply_to                  | Default |          |           | &#10003;      |
|                         | src_port                     | Default |          |           | &#10003;      |
|                         | path                         | Default |          |           | &#10003;      |
|                         | trans_depth                  | Default |          |           | &#10003;      |
|                         | reply_to                     | Default |          |           | &#10003;      |
|                         | event_name                   | Default |          |           | &#10003;      |
|                         | dest_host                    | Default |          | &#10003;  |               |
|                         | dest_port                    | Default |          |           | &#10003;      |
|                         | user_agent                   | Default |          |           | &#10003;      |
| endpoint-authentication | src_port                     | Default |          |           | &#10003;      |
|                         | ticket_encryption_type       | Default |          |           | &#10003;      |
|                         | ticket_options               | Default |          |           | &#10003;      |
|                         | request_type                 | Default |          |           | &#10003;      |
|                         | event_code                   | Default |          |           | &#10003;      |
|                         | service_name                 | Default |          |           | &#10003;      |
|                         | client_cert_subject          | Default |          |           | &#10003;      |
|                         | result_code                  | Default |          |           | &#10003;      |
|                         | issue_time                   | Default |          |           | &#10003;      |
|                         | expiry_time                  | Default |          |           | &#10003;      |
|                         | dest_port                    | Default |          |           | &#10003;      |
| endpoint-login          | src_port                     | Default |          |           | &#10003;      |
|                         | event_code                   | Default |          |           | &#10003;      |
|                         | process_name                 | Default |          |           | &#10003;      |
|                         | result_code                  | Default |          |           | &#10003;      |
|                         | src_host                     | Default |          | &#10003;  |               |
|                         | dest_port                    | Default |          |           | &#10003;      |
| file-delete             | src_port                     |         |          | &#10003;  |               |
|                         | app                          |         |          |           |               |
|                         | event_code                   |         |          | &#10003;  |               |
|                         | mime                         |         |          |           |               |
|                         | dest_host                    | Legacy  |          | &#10003;  |               |
|                         | session_id                   |         |          |           |               |
|                         | src_host                     | Legacy  |          | &#10003;  |               |
|                         | user                         | Legacy  | &#10003; | &#10003;  |               |
|                         | operation                    |         |          |           |               |
|                         | dest_port                    |         |          | &#10003;  |               |
|                         | share_path                   |         |          | &#10003;  |               |
|                         | object                       |         |          |           |               |
| file-read               | timedout                     |         |          |           | &#10003;      |
|                         | mime                         |         |          | &#10003;  |               |
|                         | extracted                    |         |          | &#10003;  |               |
|                         | duration                     |         |          |           | &#10003;      |
|                         | analyzers                    |         |          |           | &#10003;      |
|                         | connection_uid               |         |          |           | &#10003;      |
|                         | event_code                   |         |          | &#10003;  |               |
|                         | hash_md5                     |         |          |           | &#10003;      |
|                         | dest_port                    |         |          | &#10003;  |               |
|                         | app                          |         |          |           |               |
|                         | hash_sha1                    |         |          |           | &#10003;      |
|                         | local_orig                   |         |          | &#10003;  |               |
|                         | session_id                   |         |          |           |               |
|                         | missed_bytes                 |         |          |           | &#10003;      |
|                         | src_host                     | Legacy  |          | &#10003;  |               |
|                         | is_orig                      |         |          | &#10003;  |               |
|                         | share_path                   |         |          | &#10003;  |               |
|                         | extracted_cutoff             |         |          | &#10003;  |               |
|                         | overflow_bytes               |         |          | &#10003;  |               |
|                         | src_port                     |         |          | &#10003;  |               |
|                         | hash_sha256                  |         |          | &#10003;  |               |
|                         | depth                        |         |          |           | &#10003;      |
|                         | file_dir_id                  |         |          |           | &#10003;      |
|                         | bytes                        | Legacy  |          | &#10003;  |               |
|                         | file_id                      |         |          |           | &#10003;      |
|                         | log_source                   |         |          |           | &#10003;      |
|                         | dest_host                    | Legacy  |          | &#10003;  |               |
|                         | operation                    |         |          |           |               |
|                         | user                         | Legacy  | &#10003; | &#10003;  |               |
|                         | extracted_size               |         |          | &#10003;  |               |
|                         | object                       |         |          |           |               |
| file-write              | src_port                     |         |          | &#10003;  |               |
|                         | app                          |         |          |           |               |
|                         | event_code                   |         |          | &#10003;  |               |
|                         | mime                         |         |          |           |               |
|                         | dest_host                    | Legacy  |          | &#10003;  |               |
|                         | session_id                   |         |          |           |               |
|                         | src_host                     |         |          |           |               |
|                         | user                         | Legacy  | &#10003; | &#10003;  |               |
|                         | operation                    |         |          |           |               |
|                         | dest_port                    |         |          | &#10003;  |               |
|                         | share_path                   |         |          | &#10003;  |               |
|                         | object                       |         |          |           |               |
| ftp-traffic             | app                          | Default |          |           | &#10003;      |
|                         | src_port                     | Default |          |           | &#10003;      |
|                         | mime                         | Default |          |           | &#10003;      |
|                         | dest_host                    | Default |          | &#10003;  |               |
|                         | session_id                   | Default |          |           | &#10003;      |
|                         | src_host                     | Default |          | &#10003;  |               |
|                         | user                         | Default |          | &#10003;  |               |
|                         | operation                    | Default |          |           | &#10003;      |
|                         | dest_port                    | Default |          |           | &#10003;      |
|                         | object                       | Default |          |           | &#10003;      |
| http-session            | orig_filenames               | Default |          |           | &#10003;      |
|                         | additional_info              | Default |          |           | &#10003;      |
|                         | status_msg                   | Default |          |           | &#10003;      |
|                         | proxied                      | Default |          |           | &#10003;      |
|                         | tags                         | Default |          |           | &#10003;      |
| network-session         | country                      | Default |          |           | &#10003;      |
|                         | src_interface                | Default |          |           | &#10003;      |
|                         | resp_pkts                    | Default |          |           | &#10003;      |
|                         | connection_age               | Default |          |           | &#10003;      |
|                         | bytes_in                     | Default |          |           | &#10003;      |
|                         | orig_bytes                   | Default |          |           | &#10003;      |
|                         | service_name                 | Default |          |           | &#10003;      |
|                         | resp_cc                      | Default |          |           | &#10003;      |
|                         | local_orig                   | Default |          |           | &#10003;      |
|                         | orig_pkts                    | Default |          |           | &#10003;      |
|                         | orig_cc                      | Default |          |           | &#10003;      |
|                         | mbps                         | Default |          |           | &#10003;      |
|                         | missed_bytes                 | Default |          |           | &#10003;      |
|                         | history                      | Default |          |           | &#10003;      |
|                         | tunnel_parents               | Default |          |           | &#10003;      |
|                         | connection_state             | Default |          |           | &#10003;      |
|                         | duration                     | Default |          |           | &#10003;      |
|                         | local_resp                   | Default |          |           | &#10003;      |
|                         | resp_bytes                   | Default |          |           | &#10003;      |
|                         | bytes_out                    | Default |          |           | &#10003;      |
|                         | operation                    | Default |          |           | &#10003;      |
|                         | sensor_name                  | Default |          |           | &#10003;      |
|                         | user_uid                     | Default |          |           | &#10003;      |
| network-traffic         | server                       | Default |          |           | &#10003;      |
|                         | event_code                   | Default |          |           | &#10003;      |
|                         | service_name                 | Default |          |           | &#10003;      |
|                         | cipher_method                | Default |          |           | &#10003;      |
| radius-traffic          | result                       | Default |          |           | &#10003;      |
|                         | response_ttl                 | Default |          |           | &#10003;      |
|                         | user                         | Default |          | &#10003;  |               |
|                         | framed_addr                  | Default |          |           | &#10003;      |
| share-access            | share_type                   | Default |          |           | &#10003;      |
|                         | service_name                 | Default |          |           | &#10003;      |
|                         | native_file_system           | Default |          |           | &#10003;      |
| ssh-traffic             | cipher                       |         |          | &#10003;  |               |
|                         | kex_alg                      |         |          |           | &#10003;      |
|                         | mac_alg                      |         |          |           | &#10003;      |
|                         | server                       |         |          | &#10003;  |               |
|                         | host_key_alg                 |         |          | &#10003;  |               |
|                         | remote_location_longitude    |         |          |           | &#10003;      |
|                         | compression_alg              |         |          |           | &#10003;      |
|                         | version                      |         |          | &#10003;  |               |
|                         | remote_location_region       |         |          | &#10003;  |               |
|                         | client_ssh_version           |         |          | &#10003;  |               |
|                         | host_key                     |         |          | &#10003;  |               |
|                         | server_ssh_version           |         |          | &#10003;  |               |
|                         | remote_location_city         |         |          |           | &#10003;      |
|                         | remote_location_country_code |         |          | &#10003;  |               |
|                         | client                       |         |          | &#10003;  |               |
|                         | remote_location_latitude     |         |          |           | &#10003;      |
|                         | direction                    |         |          | &#10003;  |               |

