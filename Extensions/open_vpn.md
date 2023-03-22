open vpn
========

Expression
----------

product = "open vpn"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| src_ip |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field             | Status  | Core | Detection | Informational |
| ------------- | ----------------- | ------- | ---- | --------- | ------------- |
| app-activity  | app               | Default |      |           | &#10003;      |
|               | src_ip            | Default |      | &#10003;  |               |
|               | additional_info   | Default |      |           | &#10003;      |
|               | bytes             | Default |      |           | &#10003;      |
|               | src_host          | Default |      | &#10003;  |               |
|               | user              | Default |      | &#10003;  |               |
| vpn-login     | src_port          | Default |      |           | &#10003;      |
|               | duration          | Default |      |           | &#10003;      |
|               | src_translated_ip | Default |      |           | &#10003;      |
|               | group_info        | Default |      |           | &#10003;      |
|               | dest_ip           | Default |      | &#10003;  |               |
|               | login_method      | Default |      |           | &#10003;      |
|               | dest_host         | Default |      | &#10003;  |               |
|               | session_id        | Default |      |           | &#10003;      |
|               | dest_port         | Default |      |           | &#10003;      |
| vpn-logout    | src_port          |         |      |           |               |
|               | duration          |         |      |           |               |
|               | src_translated_ip |         |      |           |               |
|               | process_id        |         |      |           |               |
|               | group_info        |         |      |           |               |
|               | additional_info   |         |      |           |               |
|               | login_method      |         |      |           |               |
|               | event_name        |         |      |           |               |
|               | dest_host         | Legacy  |      |           | &#10003;      |
|               | session_id        |         |      |           |               |
|               | dest_port         |         |      |           |               |

