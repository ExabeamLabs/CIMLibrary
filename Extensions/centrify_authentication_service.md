centrify authentication service
===============================

Expression
----------

product = "centrify authentication service"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type           | Field           | Status  | Core | Detection | Informational |
| ----------------------- | --------------- | ------- | ---- | --------- | ------------- |
| endpoint-authentication | process_id      | Default |      |           | &#10003;      |
|                         | protocol        | Default |      |           | &#10003;      |
|                         | user_id         | Default |      |           | &#10003;      |
|                         | additional_info | Default |      |           | &#10003;      |
|                         | event_code      | Default |      |           | &#10003;      |
|                         | dest_ip         | Default |      | &#10003;  |               |
|                         | event_name      | Default |      |           | &#10003;      |
| endpoint-login          | src_ip          | Default |      | &#10003;  |               |
|                         | process_id      | Default |      |           | &#10003;      |
|                         | protocol        | Default |      |           | &#10003;      |
|                         | additional_info | Default |      |           | &#10003;      |
|                         | user_id         | Default |      |           | &#10003;      |
|                         | process_name    | Default |      |           | &#10003;      |
|                         | event_name      | Default |      |           | &#10003;      |
|                         | src_host        | Default |      | &#10003;  |               |
| user-password-reset     | user_id         |         |      |           |               |
|                         | additional_info |         |      |           |               |
|                         | event_code      |         |      |           |               |
|                         | event_name      |         |      |           |               |
|                         | src_host        |         |      |           |               |

