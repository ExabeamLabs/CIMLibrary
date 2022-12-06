egnyte
======

Expression
----------

product = "egnyte"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type          | Field           | Status  | Core     | Detection | Informational |
| ---------------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-authentication     | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
| app-login              | app             | Default |          |           | &#10003;      |
|                        | src_ip          | Default |          | &#10003;  |               |
|                        | event_name      | Default |          |           | &#10003;      |
|                        | event_subtype   | Default |          |           | &#10003;      |
|                        | operation       | Default |          |           | &#10003;      |
|                        | dproc           | Default |          |           | &#10003;      |
| file-permission-modify | access          | Legacy  |          | &#10003;  |               |
|                        | service_name    |         |          |           | &#10003;      |
|                        | domain          |         |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | object          |         |          |           | &#10003;      |
| group-member-add       | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | operation       |         |          |           |               |
| group-member-remove    | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | operation       |         |          |           |               |
| user-create            | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | operation       |         |          |           |               |
| user-delete            | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | operation       |         |          |           |               |
| user-disable           | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | operation       |         |          |           |               |
| user-enable            | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | operation       |         |          |           |               |
| user-mfa-disable       | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| user-mfa-enable        | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| user-modify            | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; |           |               |
|                        | operation       |         |          |           |               |
| user-password-modify   | additional_info | Default |          |           | &#10003;      |
|                        | domain          | Default |          |           | &#10003;      |
|                        | user            | Default |          | &#10003;  |               |
|                        | operation       | Default |          |           | &#10003;      |
| user-password-reset    | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; | &#10003;  |               |
|                        | operation       |         |          |           |               |
| user-permission-modify | additional_info |         |          |           |               |
|                        | domain          | Legacy  |          |           | &#10003;      |
|                        | user            | Legacy  | &#10003; |           |               |
|                        | operation       |         |          |           |               |

