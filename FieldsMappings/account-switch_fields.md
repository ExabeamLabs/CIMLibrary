Old to New-scale Field Mapping for a Specific Event
===================================================

### Old Event Type: account-switch
### New-Scale Activity Type: endpoint-login:success

This table maps old fields to the new-scale fields that comply with the Common Information Model.

| Old Fields                                                         | New-Scale Fields            |
| ------------------------------------------------------------------ | --------------------------- |
| accesses                                                           | access                      |
| target_domain                                                      | dest_domain                 |
| dest_service                                                       | dest_service_name           |
| target_user_sid                                                    | dest_user_sid               |
| user_email                                                         | email_address               |
| subject                                                            | email_subject               |
| log_type                                                           | event_category              |
| record_id                                                          | event_id                    |
| user_firstname                                                     | first_name                  |
| user_fullname                                                      | full_name                   |
| sha256_at                                                          | hash_sha256_at              |
| asset_id                                                           | host_id                     |
| user_lastname                                                      | last_name                   |
| source                                                             | legacy_product              |
| logon_id                                                           | login_id                    |
| login_type                                                         | login_type_text             |
| m_collector_name                                                   | m_collector_name            |
| m_collector_type                                                   | m_collector_type            |
| m_forwarder                                                        | m_forwarder                 |
| m_hostname                                                         | m_hostname                  |
| m_origin_collector_name                                            | m_origin_collector_name     |
| m_origin_collector_type                                            | m_origin_collector_type     |
| m_origin_hostname                                                  | m_origin_hostname           |
| m_siteid                                                           | m_siteid                    |
| m_sitename                                                         | m_sitename                  |
| activity                                                           | operation                   |
| activity_details                                                   | operation_details           |
| activity_type                                                      | operation_type              |
| parent_sha256hash                                                  | parent_hash_sha256          |
| command_line                                                       | process_command_line        |
| reason                                                             | result_reason               |
| selected_sha256                                                    | selected_hash_sha256        |
| sender                                                             | src_email_address           |
| target_sha256                                                      | target_hash_sha256          |
| account_id,<br>account_used_id                                     | account_id                  |
| account_logon_guid,<br>account_login_guid                          | account_login_guid          |
| bytes,<br>bytes_num,<br>bytes_size,<br>file_size                   | bytes                       |
| bytes_in,<br>bytes_recieved                                        | bytes_in                    |
| connection_id,<br>conn_id                                          | connection_id               |
| target_user_email,<br>recipient                                    | dest_email_address          |
| tgt_user,<br>target_user                                           | dest_user                   |
| device_name,<br>device                                             | device_name                 |
| sub_event_type,<br>event_subtype                                   | event_subtype               |
| directory,<br>file_dir,<br>file_parent,<br>f_parent                | file_dir                    |
| md5,<br>md5_sum,<br>md5_hash                                       | hash_md5                    |
| sha1,<br>sha1_sum                                                  | hash_sha1                   |
| sha256,<br>sha256_sum                                              | hash_sha256                 |
| parent_process_cmd,<br>parent_command_line,<br>parent_cmd          | parent_process_command_line |
| parent_directory,<br>parent_process_directory                      | parent_process_dir          |
| process_directory,<br>directory                                    | process_dir                 |
| process_guid,<br>target_process_guid                               | process_guid                |
| process_id,<br>pid                                                 | process_id                  |
| process_path,<br>process,<br>path                                  | process_path                |
| result,<br>outcome                                                 | result                      |
| rule,<br>rule_name                                                 | rule                        |
| service_name,<br>service                                           | service_name                |
| src_domain,<br>caller_domain                                       | src_domain                  |
| src_mac,<br>mac,<br>source_mac,<br>mac_address,<br>src_mac_address | src_mac                     |
| src_user,<br>caller_user                                           | src_user                    |
| user_logon_guid,<br>user_login_guid                                | user_login_guid             |