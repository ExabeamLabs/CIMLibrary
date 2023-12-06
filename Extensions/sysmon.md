sysmon
======

Expression
----------

product = "sysmon"

Fields
------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| log_name        | &#10003; |           |               |
| event_code      |          |           | &#10003;      |
| local_user_name |          |           |               |
| src_host        | &#10003; | &#10003;  |               |
| user            | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type   | Field                       | Status  | Core | Detection | Informational |
| --------------- | --------------------------- | ------- | ---- | --------- | ------------- |
| alert-trigger   |                             |         |      |           |               |
| dll-load        | hash_sha256                 |         |      | &#10003;  |               |
|                 | thread_id                   |         |      | &#10003;  |               |
|                 | hash_sha1                   |         |      | &#10003;  |               |
|                 | process_guid                | Legacy  |      |           | &#10003;      |
|                 | file_signature              |         |      | &#10003;  |               |
|                 | file_signature_status       |         |      | &#10003;  |               |
|                 | file_signed                 |         |      | &#10003;  |               |
|                 | hash_md5                    |         |      | &#10003;  |               |
| dns-request     | process_id                  |         |      |           | &#10003;      |
|                 | thread_id                   |         |      |           | &#10003;      |
|                 | process_guid                |         |      |           | &#10003;      |
|                 | dns_response                |         |      | &#10003;  |               |
|                 | process_name                |         |      | &#10003;  |               |
|                 | process_dir                 |         |      | &#10003;  |               |
|                 | process_path                |         |      | &#10003;  |               |
| driver-load     | hash_sha256                 | Default |      |           | &#10003;      |
|                 | process_id                  | Default |      |           | &#10003;      |
|                 | thread_id                   | Default |      |           | &#10003;      |
|                 | hash_sha1                   | Default |      |           | &#10003;      |
|                 | file_signature              | Default |      |           | &#10003;      |
|                 | file_signature_status       | Default |      |           | &#10003;      |
|                 | file_signed                 | Default |      |           | &#10003;      |
|                 | hash_md5                    | Default |      |           | &#10003;      |
| file-delete     | hash_sha256                 |         |      | &#10003;  |               |
|                 | process_id                  |         |      |           | &#10003;      |
|                 | thread_id                   |         |      |           | &#10003;      |
|                 | hash_sha1                   |         |      | &#10003;  |               |
|                 | is_executable               |         |      | &#10003;  |               |
|                 | process_guid                |         |      |           | &#10003;      |
|                 | is_archived                 |         |      |           | &#10003;      |
|                 | process_name                | Legacy  |      |           | &#10003;      |
|                 | hash_md5                    |         |      | &#10003;  |               |
|                 | process_dir                 | Legacy  |      |           | &#10003;      |
|                 | process_path                | Legacy  |      |           | &#10003;      |
| file-write      | process_id                  |         |      | &#10003;  |               |
|                 | thread_id                   |         |      |           |               |
|                 | process_guid                |         |      |           | &#10003;      |
|                 | process_name                | Legacy  |      |           | &#10003;      |
|                 | time_created                |         |      | &#10003;  |               |
|                 | process_dir                 | Legacy  |      |           | &#10003;      |
|                 | process_path                | Legacy  |      | &#10003;  |               |
| network-session | process_id                  | Default |      |           | &#10003;      |
|                 | thread_id                   | Default |      |           | &#10003;      |
|                 | process_guid                | Default |      |           | &#10003;      |
|                 | process_name                | Default |      |           | &#10003;      |
|                 | dest_ipv6                   | Default |      |           | &#10003;      |
|                 | dest_host                   | Default |      | &#10003;  |               |
|                 | process_dir                 | Default |      |           | &#10003;      |
|                 | process_path                | Default |      |           | &#10003;      |
|                 | src_ipv6                    | Default |      |           | &#10003;      |
| process-create  | hash_sha256                 | Default |      |           | &#10003;      |
|                 | hash_sha1                   | Default |      |           | &#10003;      |
|                 | process_guid                | Default |      |           | &#10003;      |
|                 | parent_process_command_line | Default |      |           | &#10003;      |
|                 | process_integrity           | Default |      |           | &#10003;      |
|                 | hash_md5                    | Default |      |           | &#10003;      |
|                 | parent_process_guid         | Default |      |           | &#10003;      |
| registry-modify | process_id                  |         |      |           | &#10003;      |
|                 | thread_id                   |         |      |           | &#10003;      |
|                 | process_guid                |         |      |           | &#10003;      |
|                 | process_name                |         |      | &#10003;  |               |
|                 | process_dir                 |         |      | &#10003;  |               |
|                 | process_path                |         |      | &#10003;  |               |

