Fields Mapping
==============

### Old Event: service-logon
### New-Scale Activity Type: endpoint-login:success

This table maps Old Event fields to the New-Scale fields that correspond to the Common Information Model.

| Old Fields                                             | New-Scale Fields            |
| ------------------------------------------------------ | --------------------------- |
| accesses                                               | access                      |
| description                                            | additional_info             |
| target_domain                                          | dest_domain                 |
| target_logon_id                                        | dest_login_id               |
| user_email                                             | email_address               |
| subject                                                | email_subject               |
| log_type                                               | event_category              |
| record_id                                              | event_id                    |
| user_firstname                                         | first_name                  |
| user_fullname                                          | full_name                   |
| sha256_at                                              | hash_sha256_at              |
| asset_id                                               | host_id                     |
| user_lastname                                          | last_name                   |
| source                                                 | legacy_product              |
| logon_id                                               | login_id                    |
| logon_type                                             | login_type                  |
| activity                                               | operation                   |
| activity_details                                       | operation_details           |
| activity_type                                          | operation_type              |
| parent_sha256hash                                      | parent_hash_sha256          |
| command_line                                           | process_command_line        |
| pid                                                    | process_id                  |
| reason                                                 | result_reason               |
| selected_sha256                                        | selected_hash_sha256        |
| sender                                                 | src_email_address           |
| target_sha256                                          | target_hash_sha256          |
| account_type                                           | user_type                   |
| bytes, bytes_num, bytes_size, file_size                | bytes                       |
| bytes_in, bytes_recieved                               | bytes_in                    |
| connection_id, conn_id                                 | connection_id               |
| target_user_email, dest_email_address, recipient       | dest_email_address          |
| tgt_user, target_user                                  | dest_user                   |
| user_sid, target_user_sid                              | dest_user_sid               |
| device_name, device                                    | device_name                 |
| sub_event_type, event_subtype                          | event_subtype               |
| directory, file_dir, file_parent, f_parent             | file_dir                    |
| md5, md5_sum, md5_hash                                 | hash_md5                    |
| sha1, sha1_sum                                         | hash_sha1                   |
| sha256, sha256_sum                                     | hash_sha256                 |
| login_type, logon_type_text, logon_type                | login_type_text             |
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