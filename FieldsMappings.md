 Field Mapping by Event
=======================

 This table maps old event types and fields to the coresponding activity types and fields in Common Information Model

| Old Event | New-Scale Activity Type| Old Fields | New-Scale Fields |
| --------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------------------------- |
| dlp-alert | [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| recipients | email_recipients|
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| rules| rule|
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| threat_score, score, risk_score| original_risk_score |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| security-alert| [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| cve| cve_id|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| recipients | email_recipients|
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome, activity_action | action|
| &nbsp;| &nbsp;| alert_name, alert| alert_name|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| malware_filename, malware_file_name| malware_file_name |
| &nbsp;| &nbsp;| threat_score, score, risk_score| original_risk_score |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| parent_process_id, parent_pid| parent_process_id |
| &nbsp;| &nbsp;| policy, policy_name| policy_name |
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome, action_blocked, action_success| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| rule_num, rule_count | rule_count|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| user, suser| user|
| &nbsp;| &nbsp;| user_id, uid | user_id |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| process-alert | [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_process_directory | dest_process_dir|
| &nbsp;| &nbsp;| target_process_name| dest_process_name |
| &nbsp;| &nbsp;| target_process | dest_process_path |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| grandparent_process| grandparent_process_path|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| parent_pid | parent_process_id |
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| target_pid, target_process_guid| dest_process_id |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| group_name, user_group | user_group_name |
| &nbsp;| &nbsp;| sid, user_sid, sid_user| user_sid|
| file-alert| [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_file_parent, src_file_dir| src_file_dir|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| network-alert | [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| connect_type | connection_type |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| rule_num | rule_count|
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| appid, application_id| app_id|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| destination_country, dest_country| dest_country|
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| log_id, resource_id, event_id| event_id|
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| dest_country, source_country | src_country |
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| alert-iot | [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| database-alert| [alert-trigger:success](ActivityTypes/alert-trigger.md) | accesses | access|
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_group | dest_group|
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| database_schema, schema| db_schema |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| os_user, user| user|
| app-activity-failed | [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome, activity_action | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| user_logon_guid, user_login_guid | user_login_guid |
| &nbsp;| &nbsp;| uid, user_uid, uuid| user_uid|
| aws-identity-loginprofile-failed| [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-screenshot-failed| [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-general-activity-failed | [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-command-failed | [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| cloud-admin-activity-failed | [app-activity:fail](ActivityTypes/app-activity.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| group| group_name|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome, activity_action | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| app-activity| [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| webconference-operations-activity | [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-general-activity| [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-general-activity| [app-activity:success](ActivityTypes/app-activity.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-identity-loginprofile | [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-command| [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-instance-screenshot | [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| cloud-admin-activity| [app-activity:success](ActivityTypes/app-activity.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| group| group_name|
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| authentication-failed | [app-authentication:fail](ActivityTypes/app-authentication.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_code, failure_reason, reason | failure_code|
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| authentication-successful | [app-authentication:success](ActivityTypes/app-authentication.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| database_name, db_name | db_name |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type_text, logon_type| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| sid, user_sid| user_sid|
| app-login | [app-authentication:success](ActivityTypes/app-authentication.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| failed-app-login| [app-login:fail](ActivityTypes/app-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| user_group | user_group_name |
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| failure_reason, reason | failure_reason|
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| aws-login-failed| [app-login:fail](ActivityTypes/app-login.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-login | [app-login:success](ActivityTypes/app-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| webconference-login | [app-login:success](ActivityTypes/app-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-login | [app-login:success](ActivityTypes/app-login.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| app-logout| [app-logout:fail](ActivityTypes/app-logout.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| app-logout| [app-logout:success](ActivityTypes/app-logout.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| group_name, group| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| url, full_url| url |
| &nbsp;| &nbsp;| sid, user_sid, user_id | user_sid|
| audit-policy-change | [audit_policy-modify:success](ActivityTypes/audit_policy-modify.md) | accesses | access|
| &nbsp;| &nbsp;| policy | audit_policy_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| login_type, logon_type, logon_type_text| login_type_text |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-accessblock-failed | [bucket-accessblock-modify:fail](ActivityTypes/bucket-accessblock-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-accessblock| [bucket-accessblock-modify:success](ActivityTypes/bucket-accessblock-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-create-failed| [bucket-create:fail](ActivityTypes/bucket-create.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-bucket-create | [bucket-create:success](ActivityTypes/bucket-create.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-create | [bucket-create:success](ActivityTypes/bucket-create.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storage-list-failed | [bucket-list:fail](ActivityTypes/bucket-list.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-storage-list| [bucket-list:success](ActivityTypes/bucket-list.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storage-list| [bucket-list:success](ActivityTypes/bucket-list.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storage-acl-failed| [bucket-permission-modify:fail](ActivityTypes/bucket-permission-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-cors-failed| [bucket-permission-modify:fail](ActivityTypes/bucket-permission-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| gcp-policy-write| [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) | bucket | bucket_name |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| device | device_name |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| service| service_name|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-storage-acl | [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-cors | [bucket-permission-modify:success](ActivityTypes/bucket-permission-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-policy-failed| [bucket-policy-modify:fail](ActivityTypes/bucket-policy-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| aws-bucket-policy | [bucket-policy-modify:success](ActivityTypes/bucket-policy-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| full_url | url |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| system-info | [certificate-request:success](ActivityTypes/certificate-request.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| system-info | [certificate-validate:success](ActivityTypes/certificate-validate.md) | target_domain| dest_domain |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| app-activity| [configuration-mfa-enable:success](ActivityTypes/configuration-mfa-enable.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| attachment | email_attachment|
| &nbsp;| &nbsp;| attachments| email_attachments |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| record_id| event_id|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| logon_type | login_type|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| pid| process_id|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| object_dn| src_ds_object_dn|
| &nbsp;| &nbsp;| object_ou| src_ds_object_ou|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| subcategory| sub_category|
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| activity_action, action, outcome | action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| file_extension, file_ext | file_ext|
| &nbsp;| &nbsp;| group, group_name| group_name|
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| http_response_code, result, response_code, result_code | http_response_code|
| &nbsp;| &nbsp;| operation, activity| operation |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| &nbsp;| &nbsp;| full_url, url| url |
| &nbsp;| &nbsp;| account_dn, user_dn| user_dn |
| &nbsp;| &nbsp;| user_id, sid | user_id |
| &nbsp;| &nbsp;| account_type, user_type| user_type |
| config-change | [configuration-modify:fail](ActivityTypes/configuration-modify.md)| accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| config-change | [configuration-modify:success](ActivityTypes/configuration-modify.md) | accesses | access|
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| logon_id | login_id|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
| &nbsp;| &nbsp;| activity_type| operation_type|
| &nbsp;| &nbsp;| parent_sha256hash| parent_hash_sha256|
| &nbsp;| &nbsp;| policy | policy_name |
| &nbsp;| &nbsp;| command_line | process_command_line|
| &nbsp;| &nbsp;| reason | result_reason |
| &nbsp;| &nbsp;| selected_sha256| selected_hash_sha256|
| &nbsp;| &nbsp;| sender | src_email_address |
| &nbsp;| &nbsp;| target_sha256| target_hash_sha256|
| &nbsp;| &nbsp;| action, outcome| action|
| &nbsp;| &nbsp;| bytes, bytes_num, bytes_size, file_size| bytes |
| &nbsp;| &nbsp;| bytes_in, bytes_recieved | bytes_in|
| &nbsp;| &nbsp;| connection_id, conn_id | connection_id |
| &nbsp;| &nbsp;| target_user_email, dest_email_address, recipient | dest_email_address|
| &nbsp;| &nbsp;| tgt_user, target_user| dest_user |
| &nbsp;| &nbsp;| device_name, device| device_name |
| &nbsp;| &nbsp;| sub_event_type, event_subtype| event_subtype |
| &nbsp;| &nbsp;| md5, md5_sum, md5_hash | hash_md5|
| &nbsp;| &nbsp;| sha1, sha1_sum | hash_sha1 |
| &nbsp;| &nbsp;| sha256, sha256_sum | hash_sha256 |
| &nbsp;| &nbsp;| parent_process_cmd, parent_command_line, parent_cmd| parent_process_command_line |
| &nbsp;| &nbsp;| parent_directory, parent_process_directory | parent_process_dir|
| &nbsp;| &nbsp;| process_directory, directory | process_dir |
| &nbsp;| &nbsp;| process_id, pid| process_id|
| &nbsp;| &nbsp;| process_path, process, path| process_path|
| &nbsp;| &nbsp;| result, outcome| result|
| &nbsp;| &nbsp;| rule, rule_name| rule|
| &nbsp;| &nbsp;| service_name, service| service_name|
| &nbsp;| &nbsp;| src_domain, caller_domain| src_domain|
| &nbsp;| &nbsp;| src_mac, mac, source_mac, mac_address, src_mac_address | src_mac |
| &nbsp;| &nbsp;| src_user, caller_user| src_user|
| database-activity-failed| [database-activity:fail](ActivityTypes/database-activity.md)| accesses | access|
| &nbsp;| &nbsp;| database_name| db_name |
| &nbsp;| &nbsp;| database_object| db_object |
| &nbsp;| &nbsp;| target_domain| dest_domain |
| &nbsp;| &nbsp;| target_user_sid| dest_user_sid |
| &nbsp;| &nbsp;| user_email | email_address |
| &nbsp;| &nbsp;| subject| email_subject |
| &nbsp;| &nbsp;| log_type | event_category|
| &nbsp;| &nbsp;| file_parent| file_dir|
| &nbsp;| &nbsp;| user_firstname | first_name|
| &nbsp;| &nbsp;| user_fullname| full_name |
| &nbsp;| &nbsp;| sha256_at| hash_sha256_at|
| &nbsp;| &nbsp;| asset_id | host_id |
| &nbsp;| &nbsp;| user_lastname| last_name |
| &nbsp;| &nbsp;| source | legacy_product|
| &nbsp;| &nbsp;| login_type | login_type_text |
| &nbsp;| &nbsp;| activity | operation |
| &nbsp;| &nbsp;| activity_details | operation_details |
