powertech identity & access manager
===================================

Expression
----------

product = "powertech identity & access manager"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| domain |      |           | &#10003;      |
| user   |      | &#10003;  |               |

Activity Types
--------------

| Activity Type  | Field      | Status  | Core | Detection | Informational |
| -------------- | ---------- | ------- | ---- | --------- | ------------- |
| endpoint-login |            |         |      |           |               |
| file-delete    | src_ip     |         |      | &#10003;  |               |
|                | event_code |         |      |           | &#10003;      |
| file-read      | src_ip     |         |      | &#10003;  |               |
|                | event_code |         |      |           | &#10003;      |
| file-write     | src_ip     |         |      | &#10003;  |               |
|                | event_code |         |      |           | &#10003;      |
| process-create | src_ip     | Default |      | &#10003;  |               |
|                | event_code | Default |      |           | &#10003;      |
| user-switch    | event_code |         |      |           | &#10003;      |
|                | dest_ip    |         |      | &#10003;  |               |

