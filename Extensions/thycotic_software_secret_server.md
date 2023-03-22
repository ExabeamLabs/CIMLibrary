thycotic software secret server
===============================

Expression
----------

product = "thycotic software secret server"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| src_ip |      |           | &#10003;      |

Activity Types
--------------

| Activity Type        | Field           | Status  | Core     | Detection | Informational |
| -------------------- | --------------- | ------- | -------- | --------- | ------------- |
| app-activity         | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | user            | Default |          | &#10003;  |               |
| app-login            |                 |         |          |           |               |
| group-member-add     | resource        |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | domain          | Legacy  |          |           | &#10003;      |
|                      | operation       |         |          |           |               |
|                      | user            | Legacy  | &#10003; | &#10003;  |               |
|                      | object          |         |          |           |               |
| group-member-remove  | resource        |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | domain          | Legacy  |          |           | &#10003;      |
|                      | operation       |         |          |           |               |
|                      | user            | Legacy  | &#10003; | &#10003;  |               |
|                      | object          |         |          |           |               |
| password-checkin     | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
| password-checkout    | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
| password-copy        | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
|                      | object          | Default |          |           | &#10003;      |
| policy-create        | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
|                      | user            | Default |          | &#10003;  |               |
| policy-modify        | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
|                      | user            | Default |          | &#10003;  |               |
| secret-copy          | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
|                      | user            | Default |          | &#10003;  |               |
| secret-create        | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
|                      | user            | Default |          | &#10003;  |               |
| secret-modify        | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
|                      | user            | Default |          | &#10003;  |               |
| user-create          | resource        |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | domain          | Legacy  |          |           | &#10003;      |
|                      | operation       |         |          |           |               |
|                      | user            | Legacy  | &#10003; | &#10003;  |               |
|                      | object          |         |          |           |               |
| user-disable         | resource        |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | domain          | Legacy  |          |           | &#10003;      |
|                      | operation       |         |          |           |               |
|                      | user            | Legacy  | &#10003; | &#10003;  |               |
|                      | object          |         |          |           |               |
| user-modify          | resource        |         |          |           |               |
|                      | additional_info |         |          |           |               |
|                      | domain          | Legacy  |          |           | &#10003;      |
|                      | operation       |         |          |           |               |
|                      | user            | Legacy  | &#10003; |           |               |
|                      | object          |         |          |           |               |
| user-password-modify | resource        | Default |          |           | &#10003;      |
|                      | additional_info | Default |          |           | &#10003;      |
|                      | domain          | Default |          |           | &#10003;      |
|                      | operation       | Default |          |           | &#10003;      |
|                      | object          | Default |          |           | &#10003;      |

