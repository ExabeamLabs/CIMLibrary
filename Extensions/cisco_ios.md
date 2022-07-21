cisco ios
=========

Expression
----------

product = "cisco ios"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| src_ip |      | &#10003;  |               |

Activity Types
--------------

| Activity Type        | Field          | Status  | Core | Detection | Informational |
| -------------------- | -------------- | ------- | ---- | --------- | ------------- |
| configuration-modify | event_code     |         |      |           |               |
|                      | event_name     |         |      |           |               |
|                      | src_host       |         |      | &#10003;  |               |
|                      | event_category |         |      |           |               |
|                      | user           |         |      |           |               |
| endpoint-login       | src_port       | Default |      |           | &#10003;      |
|                      | event_code     | Default |      |           | &#10003;      |
| network-session      | src_interface  | Default |      |           | &#10003;      |
|                      | packets        | Default |      |           | &#10003;      |
| process-create       | user           | Default |      | &#10003;  |               |

