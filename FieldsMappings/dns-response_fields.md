Fields Mapping
==============

### Old Event: dns-response
### New-Scale Activity Type: dns-response:success

This table maps Old Event fields to the New-Scale fields that correspond to the Common Information Model.

| Old Fields                                             | New-Scale Fields            |
| ------------------------------------------------------ | --------------------------- |
| accesses                                               | access                      |
| target_domain                                          | dest_domain                 |
| query                                                  | dns_query                   |
| query_flags                                            | dns_query_flags             |
| query_type                                             | dns_query_type              |
| response                                               | dns_response                |
| response_flags                                         | dns_response_flags          |
| user_email                                             | email_address               |
| subject                                                | email_subject               |
| log_type                                               | event_category              |
| user_firstname                                         | first_name                  |
| user_fullname                                          | full_name                   |
| sha256_at                                              | hash_sha256_at              |
| asset_id                                               | host_id                     |
| user_lastname                                          | last_name                   |
| source                                                 | legacy_product              |
| login_type                                             | login_type_text             |
| activity                                               | operation                   |
| activity_details                                       | operation_details           |
| activity_type                                          | operation_type              |
| parent_sha256hash                                      | parent_hash_sha256          |
| policy                                                 | policy_name                 |
| command_line                                           | process_command_line        |
| pid                                                    | process_id                  |
| reason                                                 | result_reason               |
| selected_sha256                                        | selected_hash_sha256        |
| sender                                                 | src_email_address           |
| target_sha256                                          | target_hash_sha256          |
| bytes, bytes_num, bytes_size, file_size                | bytes                       |
| bytes_in, bytes_recieved                               | bytes_in                    |
| connection_id, conn_id                                 | connection_id               |
| target_user_email, dest_email_address, recipient       | dest_email_address          |
| tgt_user, target_user                                  | dest_user                   |
| user_sid, target_user_sid                              | dest_user_sid               |
| device_name, device                                    | device_name                 |
| sub_event_type, event_subtype                          | event_subtype               |
| failure_reason, reason                                 | failure_reason              |
| directory, file_dir, file_parent, f_parent             | file_dir                    |
| md5, md5_sum, md5_hash                                 | hash_md5                    |
| sha1, sha1_sum                                         | hash_sha1                   |
| sha256, sha256_sum                                     | hash_sha256                 |
| parent_process_cmd, parent_command_line, parent_cmd    | parent_process_command_line |
| parent_directory, parent_process_directory             | parent_process_dir          |
| process_directory, directory                           | process_dir                 |
| process_path, process, path                            | process_path                |
| result, outcome                                        | result                      |
| rule, rule_name                                        | rule                        |
| service_name, service                                  | service_name                |
| src_domain, caller_domain                              | src_domain                  |
| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac                     |
| src_user, caller_user                                  | src_user                    |