singularity platform
====================

Expression
----------

product = "sentinelone"

Fields
------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| process_name     |      |           | &#10003;      |
| bytes            |      |           | &#10003;      |
| domain           |      |           | &#10003;      |
| user_sid         |      |           | &#10003;      |
| domain_user_name |      |           |               |
| user             |      |           | &#10003;      |

Activity Types
--------------

| Activity Type         | Field                | Status  | Core     | Detection | Informational |
| --------------------- | -------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger         | file_path            | Legacy  |          |           | &#10003;      |
|                       | file_ext             |         |          |           |               |
|                       | agent_id             |         |          |           |               |
|                       | file_name            | Legacy  | &#10003; |           |               |
|                       | process_name         | Legacy  |          | &#10003;  |               |
|                       | dest_ip              | Legacy  | &#10003; | &#10003;  |               |
|                       | file_dir             | Legacy  |          |           | &#10003;      |
|                       | dest_host            | Legacy  |          | &#10003;  |               |
| app-activity          | src_ip               | Default |          | &#10003;  |               |
|                       | src_mac              | Default |          |           | &#10003;      |
|                       | additional_info      | Default |          |           | &#10003;      |
|                       | hash_md5             | Default |          |           | &#10003;      |
| dns-request           | process_id           |         |          |           |               |
|                       | hash_sha1            |         |          |           |               |
|                       | agent_id             |         |          |           |               |
|                       | alert_severity       |         |          |           |               |
|                       | process_dir          |         |          |           |               |
|                       | src_host             | Legacy  | &#10003; | &#10003;  |               |
|                       | alert_type           |         |          |           |               |
|                       | hash_sha256          |         |          |           |               |
|                       | process_name         |         |          |           |               |
|                       | alert_id             |         |          |           |               |
|                       | hash_md5             |         |          |           |               |
|                       | event_name           |         |          |           |               |
|                       | process_path         |         |          |           |               |
|                       | alert_name           |         |          |           |               |
|                       | user_agent           |         |          |           |               |
| dns-response          | process_id           |         |          |           |               |
|                       | hash_sha1            |         |          |           |               |
|                       | agent_id             |         |          |           |               |
|                       | alert_severity       |         |          |           |               |
|                       | process_dir          |         |          |           |               |
|                       | alert_type           |         |          |           |               |
|                       | hash_sha256          |         |          |           |               |
|                       | process_name         |         |          |           |               |
|                       | alert_id             |         |          |           |               |
|                       | hash_md5             |         |          |           |               |
|                       | event_name           |         |          |           |               |
|                       | process_path         |         |          |           |               |
|                       | alert_name           |         |          |           |               |
|                       | user_agent           |         |          |           |               |
| file-delete           | src_ip               |         |          |           |               |
|                       | dest_ip              |         |          |           |               |
|                       | event_name           |         |          |           |               |
| file-read             | src_ip               |         |          |           |               |
|                       | agent_id             |         |          |           |               |
|                       | alert_severity       |         |          |           |               |
|                       | dest_ip              |         |          |           |               |
|                       | alert_id             |         |          |           |               |
|                       | src_host             | Legacy  |          | &#10003;  |               |
|                       | alert_name           |         |          |           |               |
|                       | alert_type           |         |          |           |               |
| file-write            | src_ip               |         |          |           |               |
|                       | dest_ip              |         |          |           |               |
|                       | event_name           |         |          |           |               |
| http-session          | agent_id             | Default |          |           | &#10003;      |
|                       | process_name         | Default |          |           | &#10003;      |
|                       | alert_id             | Default |          |           | &#10003;      |
|                       | malware_url          | Default |          |           | &#10003;      |
|                       | src_host             | Default |          | &#10003;  |               |
| network-traffic       | agent_id             | Default |          |           | &#10003;      |
|                       | process_name         | Default |          |           | &#10003;      |
|                       | alert_severity       | Default |          |           | &#10003;      |
|                       | alert_id             | Default |          |           | &#10003;      |
|                       | dest_host            | Default |          | &#10003;  |               |
|                       | event_name           | Default |          |           | &#10003;      |
|                       | process_dir          | Default |          |           | &#10003;      |
|                       | process_path         | Default |          |           | &#10003;      |
|                       | alert_name           | Default |          |           | &#10003;      |
|                       | alert_type           | Default |          |           | &#10003;      |
| process-create        | src_ip               | Default |          | &#10003;  |               |
|                       | hash_sha256          | Default |          |           | &#10003;      |
|                       | agent_id             | Default |          |           | &#10003;      |
|                       | dest_ip              | Default |          | &#10003;  |               |
|                       | object               | Default |          |           | &#10003;      |
| registry-modify       | src_ip               |         |          |           |               |
|                       | agent_id             |         |          |           |               |
|                       | process_name         |         |          |           |               |
|                       | alert_severity       |         |          |           |               |
|                       | dest_ip              |         |          |           |               |
|                       | alert_id             |         |          |           |               |
|                       | alert_name           |         |          |           |               |
|                       | alert_type           |         |          |           |               |
|                       | object               |         |          |           |               |
| scheduled_task-create | src_ip               |         |          |           |               |
|                       | hash_sha256          |         |          |           |               |
|                       | process_id           | Legacy  |          |           | &#10003;      |
|                       | hash_sha1            |         |          |           |               |
|                       | process_name         | Legacy  | &#10003; | &#10003;  |               |
|                       | dest_ip              |         |          |           |               |
|                       | hash_md5             |         |          |           |               |
|                       | event_name           |         |          |           |               |
|                       | process_dir          | Legacy  |          |           | &#10003;      |
|                       | process_path         | Legacy  |          | &#10003;  |               |
|                       | process_command_line |         |          |           |               |
|                       | user_agent           |         |          |           |               |

