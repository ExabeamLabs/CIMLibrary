ping identity
=============

Expression
----------

product = "ping identity"

Fields
------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| src_ip        |      |           | &#10003;      |
| protocol      |      |           | &#10003;      |
| connection_id |      |           | &#10003;      |

Activity Types
--------------

| Activity Type        | Field            | Status  | Core | Detection | Informational |
| -------------------- | ---------------- | ------- | ---- | --------- | ------------- |
| app-activity         | additional_info  | Default |      |           | &#10003;      |
|                      | domain           | Default |      |           | &#10003;      |
|                      | event_name       | Default |      |           | &#10003;      |
|                      | category         | Default |      |           | &#10003;      |
|                      | user             | Default |      | &#10003;  |               |
|                      | user_agent       | Default |      |           | &#10003;      |
|                      | url              | Default |      |           | &#10003;      |
|                      | alert_name       | Default |      |           | &#10003;      |
| app-authentication   | local_user_id    | Default |      |           | &#10003;      |
|                      | role             | Default |      |           | &#10003;      |
|                      | src_host         | Default |      | &#10003;  |               |
|                      | auth_method      | Default |      |           | &#10003;      |
|                      | additional_info  | Default |      |           | &#10003;      |
|                      | dest_ip          | Default |      | &#10003;  |               |
|                      | browser          | Default |      |           | &#10003;      |
|                      | dest_host        | Default |      | &#10003;  |               |
|                      | event_name       | Default |      |           | &#10003;      |
|                      | operating_system | Default |      |           | &#10003;      |
|                      | response_time    | Default |      |           | &#10003;      |
|                      | attributes       | Default |      |           | &#10003;      |
|                      | device           | Default |      |           | &#10003;      |
|                      | tracking_id      | Default |      |           | &#10003;      |
|                      | user_agent       | Default |      |           | &#10003;      |
|                      | adopter_id       | Default |      |           | &#10003;      |
| app-login            | country          | Default |      |           | &#10003;      |
|                      | requested_app    | Default |      |           | &#10003;      |
|                      | src_host         | Default |      | &#10003;  |               |
|                      | url              | Default |      |           | &#10003;      |
|                      | src_ip           | Default |      | &#10003;  |               |
|                      | auth_method      | Default |      |           | &#10003;      |
|                      | additional_info  | Default |      |           | &#10003;      |
|                      | dest_ip          | Default |      | &#10003;  |               |
|                      | operating_system | Default |      |           | &#10003;      |
|                      | dest_host        | Default |      | &#10003;  |               |
|                      | event_name       | Default |      |           | &#10003;      |
|                      | requested_app_id | Default |      |           | &#10003;      |
|                      | category         | Default |      |           | &#10003;      |
|                      | alert_name       | Default |      |           | &#10003;      |
|                      | user_agent       | Default |      |           | &#10003;      |
| user-password-modify | local_user_id    | Default |      |           | &#10003;      |
|                      | role             | Default |      |           | &#10003;      |
|                      | response_time    | Default |      |           | &#10003;      |
|                      | attributes       | Default |      |           | &#10003;      |
|                      | user             | Default |      | &#10003;  |               |
|                      | tracking_id      | Default |      |           | &#10003;      |
|                      | adopter_id       | Default |      |           | &#10003;      |
| user-password-reset  | local_user_id    |         |      |           |               |
|                      | role             |         |      |           |               |
|                      | response_time    |         |      |           |               |
|                      | attributes       |         |      |           |               |
|                      | tracking_id      |         |      |           |               |
|                      | adopter_id       |         |      |           |               |
| vpn-login            | country          | Default |      |           | &#10003;      |
|                      | requested_app    | Default |      |           | &#10003;      |
|                      | operating_system | Default |      |           | &#10003;      |
|                      | requested_app_id | Default |      |           | &#10003;      |
|                      | device           | Default |      |           | &#10003;      |

