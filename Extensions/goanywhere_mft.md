goanywhere mft
==============

Expression
----------

product = "goanywhere mft"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type  | Field      | Status  | Core     | Detection | Informational |
| -------------- | ---------- | ------- | -------- | --------- | ------------- |
| endpoint-login | src_ip     | Default |          | &#10003;  |               |
|                | dest_ip    | Default |          | &#10003;  |               |
|                | event_name | Default |          |           | &#10003;      |
| file-delete    | src_ip     |         |          |           |               |
|                | dest_ip    |         |          |           |               |
|                | src_host   | Legacy  |          | &#10003;  |               |
|                | user       | Legacy  | &#10003; | &#10003;  |               |
| file-download  | src_ip     |         |          |           |               |
|                | dest_ip    |         |          |           |               |
|                | dest_host  | Legacy  |          |           | &#10003;      |
|                | user       | Legacy  | &#10003; | &#10003;  |               |
| file-upload    | src_ip     |         |          |           |               |
|                | dest_ip    |         |          |           |               |
|                | src_host   | Legacy  |          |           | &#10003;      |
|                | user       | Legacy  | &#10003; | &#10003;  |               |

