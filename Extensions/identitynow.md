identitynow
===========

Expression
----------

product = "identitynow"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type        | Field           | Status  | Core     | Detection | Informational |
| -------------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-activity         | src_ip          | Default |          | &#10003;  |               |
|                      | operation_type  | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | fingerprint     | Default |          |           | &#10003;      |
|                      | event_name      | Default |          |           | &#10003;      |
|                      | event_subtype   | Default |          |           | &#10003;      |
|                      | src_host        | Default |          | &#10003;  |               |
| app-authentication   | src_ip          | Default |          | &#10003;  |               |
|                      | operation_type  | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | fingerprint     | Default |          |           | &#10003;      |
|                      | event_name      | Default |          |           | &#10003;      |
|                      | event_subtype   | Default |          |           | &#10003;      |
|                      | src_host        | Default |          | &#10003;  |               |
|                      | operation       | Default |          |           | &#10003;      |
| app-login            | src_ip          | Default |          | &#10003;  |               |
|                      | operation_type  | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | fingerprint     | Default |          |           | &#10003;      |
|                      | event_name      | Default |          |           | &#10003;      |
|                      | event_subtype   | Default |          |           | &#10003;      |
|                      | src_host        | Default |          | &#10003;  |               |
|                      | operation       | Default |          |           | &#10003;      |
| user-modify          | src_ip          |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | fingerprint     |         |          |           |               |
|                      | src_host        | Legacy  |          |           | &#10003;      |
|                      | event_subtype   |         |          |           |               |
|                      | user            | Legacy  | &#10003; |           |               |
|                      | operation       |         |          |           |               |
| user-password-modify | src_ip          | Default |          | &#10003;  |               |
|                      | dest_user_ou    | Default |          |           | &#10003;      |
|                      | operation_type  | Default |          |           | &#10003;      |
|                      | event_name      | Default |          |           | &#10003;      |
|                      | src_host        | Default |          | &#10003;  |               |
|                      | operation       | Default |          |           | &#10003;      |
| user-unlock          | src_ip          |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | fingerprint     |         |          |           |               |
|                      | src_host        |         |          |           |               |
|                      | event_subtype   |         |          |           |               |
|                      | user            | Legacy  | &#10003; | &#10003;  |               |
|                      | operation       |         |          |           |               |

