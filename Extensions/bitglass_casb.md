bitglass casb
=============

Expression
----------

product = "bitglass casb"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| os               |          | &#10003;  |               |
| domain           |          | &#10003;  |               |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |
| user_agent       |          | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field           | Status  | Core     | Detection | Informational |
| ------------- | --------------- | ------- | -------- | --------- | ------------- |
| alert-trigger | file_ext        |         |          |           |               |
|               | additional_info |         |          |           |               |
|               | file_name       | Legacy  | &#10003; |           |               |
|               | process_name    | Legacy  |          | &#10003;  |               |
|               | user            | Legacy  |          | &#10003;  |               |
|               | target          |         |          |           |               |
| app-login     | src_ip          | Default |          | &#10003;  |               |
|               | additional_info | Default |          |           | &#10003;      |
|               | dest_ip         | Default |          | &#10003;  |               |
|               | event_name      | Default |          |           | &#10003;      |
|               | user_group_name | Default |          |           | &#10003;      |
| email-send    | src_ip          | Default |          | &#10003;  |               |
| file-download | additional_info |         |          |           | &#10003;      |
|               | dest_ip         |         |          | &#10003;  |               |
|               | event_name      |         |          |           | &#10003;      |
|               | user_group_name |         |          | &#10003;  |               |
| file-read     | src_ip          |         |          | &#10003;  |               |
|               | file_url        |         |          | &#10003;  |               |
|               | access          | Legacy  |          | &#10003;  |               |
| file-write    | src_ip          |         |          | &#10003;  |               |
|               | file_url        |         |          | &#10003;  |               |
|               | access          | Legacy  |          | &#10003;  |               |

