event viewer - security
=======================

Expression
----------

product = "event viewer - security"

Fields
------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| login_id       |          |           | &#10003;      |
| event_id       |          |           | &#10003;      |
| log_name       |          |           | &#10003;      |
| user_id        |          |           | &#10003;      |
| event_code     |          |           | &#10003;      |
| domain         |          | &#10003;  |               |
| event_name     |          |           | &#10003;      |
| correlation_id |          |           | &#10003;      |
| src_host       | &#10003; | &#10003;  |               |
| user           | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type     | Field           | Status  | Core | Detection | Informational |
| ----------------- | --------------- | ------- | ---- | --------- | ------------- |
| ds_object-create  |                 |         |      |           |               |
| ds_object-delete  |                 |         |      |           |               |
| ds_object-modify  | access          | Default |      |           | &#10003;      |
|                   | access_mask     | Default |      |           | &#10003;      |
|                   | attribute       | Default |      |           | &#10003;      |
|                   | attribute_value | Default |      |           | &#10003;      |
|                   | operation       | Default |      |           | &#10003;      |
| ds_object-move    |                 |         |      |           |               |
| ds_object-restore |                 |         |      |           |               |
| endpoint-delete   |                 |         |      |           |               |
| endpoint-modify   | old_attribute   |         |      | &#10003;  |               |
|                   | new_attribute   |         |      | &#10003;  |               |
|                   | attribute       |         |      |           | &#10003;      |
| share-access      | file_ext        | Default |      |           | &#10003;      |
|                   | access          | Default |      |           | &#10003;      |
|                   | additional_info | Default |      |           | &#10003;      |
|                   | file_name       | Default |      |           | &#10003;      |
|                   | process_name    | Default |      |           | &#10003;      |
|                   | file_dir        | Default |      |           | &#10003;      |
|                   | user_sid        | Default |      |           | &#10003;      |
|                   | process_dir     | Default |      |           | &#10003;      |
|                   | process_path    | Default |      |           | &#10003;      |
|                   | object          | Default |      |           | &#10003;      |

