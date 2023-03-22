zoom
====

Expression
----------

product = "zoom"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| operation |      |           | &#10003;      |

Activity Types
--------------

| Activity Type       | Field            | Status  | Core | Detection | Informational |
| ------------------- | ---------------- | ------- | ---- | --------- | ------------- |
| app-login           | src_ip           | Default |      | &#10003;  |               |
|                     | app_version      | Default |      |           | &#10003;      |
|                     | additional_info  | Default |      |           | &#10003;      |
|                     | client_type      | Default |      |           | &#10003;      |
| meeting-create      | meeting_topic    | Legacy  |      |           | &#10003;      |
|                     | meeting_timezone | Legacy  |      |           | &#10003;      |
|                     | meeting_type     | Legacy  |      |           | &#10003;      |
|                     | meeting_duration | Legacy  |      |           | &#10003;      |
|                     | meeting_number   | Legacy  |      |           | &#10003;      |
| meeting-end         | meeting_topic    | Legacy  |      |           | &#10003;      |
|                     | meeting_timezone | Legacy  |      |           | &#10003;      |
|                     | meeting_type     | Legacy  |      |           | &#10003;      |
|                     | meeting_duration | Legacy  |      |           | &#10003;      |
|                     | meeting_number   | Legacy  |      |           | &#10003;      |
| meeting-member-join | member_id        |         |      |           |               |
|                     | meeting_topic    | Legacy  |      |           | &#10003;      |
|                     | meeting_timezone | Legacy  |      |           | &#10003;      |
|                     | meeting_type     | Legacy  |      |           | &#10003;      |
|                     | meeting_number   | Legacy  |      |           | &#10003;      |
| meeting-modify      | old_password     | Legacy  |      |           | &#10003;      |
|                     | new_password     | Legacy  |      |           | &#10003;      |
|                     | meeting_number   | Legacy  |      |           | &#10003;      |
| meeting-start       | meeting_topic    | Legacy  |      |           | &#10003;      |
|                     | meeting_timezone | Legacy  |      |           | &#10003;      |
|                     | meeting_type     | Legacy  |      |           | &#10003;      |
|                     | meeting_number   | Legacy  |      |           | &#10003;      |

