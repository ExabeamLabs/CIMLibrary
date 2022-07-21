carbon black cloud endpoint standard
====================================

Expression
----------

product = "carbon black ces"

Fields
------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| src_ip |          | &#10003;  |               |
| domain |          | &#10003;  |               |
| user   | &#10003; |           |               |

Activity Types
--------------

| Activity Type   | Field                | Status  | Core | Detection | Informational |
| --------------- | -------------------- | ------- | ---- | --------- | ------------- |
| app-login       |                      |         |      |           |               |
| file-read       | selected_hash_sha256 |         |      | &#10003;  |               |
|                 | target_hash_sha256   |         |      | &#10003;  |               |
|                 | alert_severity       |         |      | &#10003;  |               |
|                 | target_md5hash       |         |      | &#10003;  |               |
|                 | process_dir          | Legacy  |      |           | &#10003;      |
|                 | src_host             | Legacy  |      | &#10003;  |               |
|                 | alert_type           |         |      | &#10003;  |               |
|                 | hash_sha256          |         |      | &#10003;  |               |
|                 | selected_md5hash     |         |      | &#10003;  |               |
|                 | web_domain           |         |      | &#10003;  |               |
|                 | process_name         | Legacy  |      |           | &#10003;      |
|                 | parent_hash_sha256   |         |      | &#10003;  |               |
|                 | dest_ip              |         |      | &#10003;  |               |
|                 | alert_id             |         |      |           | &#10003;      |
|                 | hash_md5             |         |      | &#10003;  |               |
|                 | process_path         | Legacy  |      | &#10003;  |               |
|                 | parent_md5hash       |         |      | &#10003;  |               |
|                 | alert_name           |         |      | &#10003;  |               |
| file-write      | selected_hash_sha256 |         |      | &#10003;  |               |
|                 | target_hash_sha256   |         |      | &#10003;  |               |
|                 | alert_severity       |         |      | &#10003;  |               |
|                 | target_md5hash       |         |      | &#10003;  |               |
|                 | process_dir          | Legacy  |      |           | &#10003;      |
|                 | src_host             |         |      | &#10003;  |               |
|                 | alert_type           |         |      | &#10003;  |               |
|                 | hash_sha256          |         |      | &#10003;  |               |
|                 | selected_md5hash     |         |      | &#10003;  |               |
|                 | web_domain           |         |      | &#10003;  |               |
|                 | process_name         | Legacy  |      |           | &#10003;      |
|                 | parent_hash_sha256   |         |      | &#10003;  |               |
|                 | dest_ip              |         |      | &#10003;  |               |
|                 | alert_id             |         |      |           | &#10003;      |
|                 | hash_md5             |         |      | &#10003;  |               |
|                 | process_path         | Legacy  |      | &#10003;  |               |
|                 | parent_md5hash       |         |      | &#10003;  |               |
|                 | alert_name           |         |      | &#10003;  |               |
| network-session | selected_hash_sha256 | Default |      |           | &#10003;      |
|                 | file_path            | Default |      |           | &#10003;      |
|                 | target_hash_sha256   | Default |      |           | &#10003;      |
|                 | file_name            | Default |      |           | &#10003;      |
|                 | alert_severity       | Default |      |           | &#10003;      |
|                 | file_dir             | Default |      |           | &#10003;      |
|                 | target_md5hash       | Default |      |           | &#10003;      |
|                 | process_dir          | Default |      |           | &#10003;      |
|                 | src_host             | Default |      | &#10003;  |               |
|                 | alert_type           | Default |      |           | &#10003;      |
|                 | hash_sha256          | Default |      |           | &#10003;      |
|                 | selected_md5hash     | Default |      |           | &#10003;      |
|                 | web_domain           | Default |      |           | &#10003;      |
|                 | process_name         | Default |      |           | &#10003;      |
|                 | parent_hash_sha256   | Default |      |           | &#10003;      |
|                 | alert_id             | Default |      |           | &#10003;      |
|                 | hash_md5             | Default |      |           | &#10003;      |
|                 | process_path         | Default |      |           | &#10003;      |
|                 | parent_md5hash       | Default |      |           | &#10003;      |
|                 | alert_name           | Default |      |           | &#10003;      |
| process-create  | selected_hash_sha256 | Default |      |           | &#10003;      |
|                 | hash_sha256          | Default |      |           | &#10003;      |
|                 | file_path            | Default |      |           | &#10003;      |
|                 | target_hash_sha256   | Default |      |           | &#10003;      |
|                 | selected_md5hash     | Default |      |           | &#10003;      |
|                 | file_name            | Default |      |           | &#10003;      |
|                 | parent_hash_sha256   | Default |      |           | &#10003;      |
|                 | dest_ip              | Default |      | &#10003;  |               |
|                 | file_dir             | Default |      |           | &#10003;      |
|                 | hash_md5             | Default |      |           | &#10003;      |
|                 | target_md5hash       | Default |      |           | &#10003;      |
|                 | parent_md5hash       | Default |      |           | &#10003;      |

