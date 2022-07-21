fortinet utm
============

Expression
----------

product = fortinet utm

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type           | Field           | Status  | Core     | Detection | Informational |
| ----------------------- | --------------- | ------- | -------- | --------- | ------------- |
| alert-trigger           | src_ip          | Legacy  | &#10003; | &#10003;  |               |
|                         | src_port        | Legacy  |          |           | &#10003;      |
|                         | protocol        | Legacy  |          | &#10003;  |               |
|                         | additional_info |         |          |           |               |
|                         | dest_ip         | Legacy  | &#10003; | &#10003;  |               |
|                         | action          | Legacy  |          |           | &#10003;      |
|                         | src_host        | Legacy  | &#10003; | &#10003;  |               |
|                         | user            | Legacy  |          | &#10003;  |               |
|                         | dest_port       | Legacy  |          | &#10003;  |               |
|                         | target          |         |          |           |               |
| app-activity            | src_ip          | Default |          | &#10003;  |               |
|                         | src_port        | Default |          |           | &#10003;      |
|                         | web_domain      | Default |          |           | &#10003;      |
|                         | dest_ip         | Default |          | &#10003;  |               |
|                         | event_name      | Default |          |           | &#10003;      |
|                         | event_subtype   | Default |          |           | &#10003;      |
|                         | category        | Default |          |           | &#10003;      |
|                         | user            | Default | &#10003; | &#10003;  |               |
|                         | auth_server     | Default |          |           | &#10003;      |
|                         | uri             | Default |          |           | &#10003;      |
|                         | dest_port       | Default |          |           | &#10003;      |
| endpoint-authentication | src_ip          | Default |          | &#10003;  |               |
|                         | dest_ip         | Default |          | &#10003;  |               |
| http-request            | application     | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |
|                         | service_name    | Default |          |           | &#10003;      |
|                         | event_name      | Default |          |           | &#10003;      |
|                         | event_subtype   | Default |          |           | &#10003;      |
|                         | operation       | Default |          |           | &#10003;      |
|                         | auth_server     | Default |          |           | &#10003;      |
| http-session            | policy_id       | Default |          |           | &#10003;      |
|                         | group_name      | Default |          |           | &#10003;      |
|                         | additional_info | Default |          |           | &#10003;      |

