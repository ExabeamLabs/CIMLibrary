forescout counteract
====================

Expression
----------

product = "forescout counteract"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type          | Field           | Status  | Core | Detection | Informational |
| ---------------------- | --------------- | ------- | ---- | --------- | ------------- |
| configuration-modify   | src_ip          |         |      |           |               |
|                        | additional_info |         |      |           |               |
|                        | dest_ip         |         |      |           |               |
|                        | session_id      |         |      |           |               |
|                        | user            |         |      |           |               |
|                        | operation       |         |      |           |               |
|                        | object          |         |      |           |               |
| endpoint-policy-verify | host_ip         | Default |      |           | &#10003;      |
|                        | dest_mac        | Default |      |           | &#10003;      |
|                        | dest_ip         | Default |      | &#10003;  |               |
|                        | event_name      | Default |      |           | &#10003;      |
|                        | user            | Default |      | &#10003;  |               |
| network-session        |                 |         |      |           |               |

