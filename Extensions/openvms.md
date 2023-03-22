openvms
=======

Expression
----------

product = "openvms"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type  | Field           | Status  | Core     | Detection | Informational |
| -------------- | --------------- | ------- | -------- | --------- | ------------- |
| endpoint-login | process_id      | Default |          |           | &#10003;      |
|                | additional_info | Default |          |           | &#10003;      |
|                | process_name    | Default |          |           | &#10003;      |
|                | event_name      | Default |          |           | &#10003;      |
| file-delete    | process_id      |         |          |           |               |
|                | access          | Legacy  |          | &#10003;  |               |
|                | additional_info |         |          |           |               |
|                | process_name    | Legacy  |          |           | &#10003;      |
|                | event_name      |         |          |           |               |
|                | user            | Legacy  | &#10003; | &#10003;  |               |
| file-read      | process_id      |         |          |           |               |
|                | access          | Legacy  |          | &#10003;  |               |
|                | additional_info |         |          |           |               |
|                | process_name    | Legacy  |          |           | &#10003;      |
|                | event_name      |         |          |           |               |
|                | user            | Legacy  | &#10003; | &#10003;  |               |

