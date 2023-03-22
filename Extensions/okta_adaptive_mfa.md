okta adaptive mfa
=================

Expression
----------

product = "okta adaptive mfa"

Fields
------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| src_ip |          | &#10003;  |               |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type       | Field            | Status  | Core | Detection | Informational |
| ------------------- | ---------------- | ------- | ---- | --------- | ------------- |
| app-activity        | object_type      | Default |      |           | &#10003;      |
|                     | group_name       | Default |      |           | &#10003;      |
|                     | location_country | Default |      |           | &#10003;      |
|                     | dest_user        | Default |      | &#10003;  |               |
|                     | location_state   | Default |      |           | &#10003;      |
|                     | uri              | Default |      |           | &#10003;      |
|                     | url              | Default |      |           | &#10003;      |
|                     | additional_info  | Default |      |           | &#10003;      |
|                     | location_city    | Default |      |           | &#10003;      |
|                     | members          | Default |      |           | &#10003;      |
|                     | assigned_apps    | Default |      |           | &#10003;      |
|                     | user_agent       | Default |      |           | &#10003;      |
|                     | object           | Default |      |           | &#10003;      |
| app-authentication  | object_type      | Default |      |           | &#10003;      |
|                     | additional_info  | Default |      |           | &#10003;      |
|                     | location_country | Default |      |           | &#10003;      |
|                     | location_city    | Default |      |           | &#10003;      |
|                     | event_name       | Default |      |           | &#10003;      |
|                     | dest_user        | Default |      | &#10003;  |               |
|                     | location_state   | Default |      |           | &#10003;      |
|                     | uri              | Default |      |           | &#10003;      |
|                     | operation        | Default |      |           | &#10003;      |
|                     | user_agent       | Default |      |           | &#10003;      |
|                     | url              | Default |      |           | &#10003;      |
|                     | object           | Default |      |           | &#10003;      |
| app-login           | user_agent       | Default |      |           | &#10003;      |
| group-member-add    | group_type       | Legacy  |      |           | &#10003;      |
| user-create         | app              |         |      |           |               |
|                     | object_type      |         |      |           |               |
|                     | additional_info  |         |      |           |               |
|                     | browser          |         |      |           |               |
|                     | operation        |         |      |           |               |
|                     | uri              |         |      |           |               |
|                     | user_agent       |         |      |           |               |
|                     | object           |         |      |           |               |
| user-lock           | group_name       |         |      |           | &#10003;      |
| user-password-reset | app              |         |      |           |               |
|                     | object_type      |         |      |           |               |
|                     | additional_info  |         |      |           |               |
|                     | browser          |         |      |           |               |
|                     | operation        |         |      |           |               |
|                     | uri              |         |      |           |               |
|                     | user_agent       |         |      |           |               |
|                     | object           |         |      |           |               |

