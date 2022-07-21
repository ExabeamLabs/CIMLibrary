palo alto aperture
==================

Expression
----------

product = "palo alto aperture"

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| domain |      |           | &#10003;      |
| user   |      |           | &#10003;      |

Activity Types
--------------

| Activity Type       | Field           | Status  | Core     | Detection | Informational |
| ------------------- | --------------- | ------- | -------- | --------- | ------------- |
| alert-trigger       | src_ip          | Legacy  | &#10003; | &#10003;  |               |
|                     | additional_info |         |          |           |               |
|                     | item_type       |         |          |           |               |
|                     | dest_ip         | Legacy  | &#10003; | &#10003;  |               |
|                     | item_creator    |         |          |           |               |
|                     | collaborators   |         |          |           |               |
|                     | last_name       |         |          |           |               |
|                     | item_name       |         |          |           |               |
|                     | user            | Legacy  |          | &#10003;  |               |
|                     | first_name      |         |          |           |               |
| app-activity        | src_ip          | Default |          | &#10003;  |               |
| app-login           | src_ip          | Default |          | &#10003;  |               |
| audit_policy-modify | src_ip          |         |          | &#10003;  |               |
|                     | operation       |         |          |           | &#10003;      |
| file-delete         | src_ip          |         |          | &#10003;  |               |
|                     | access          | Legacy  |          | &#10003;  |               |
| file-read           | src_ip          |         |          | &#10003;  |               |
|                     | access          | Legacy  |          | &#10003;  |               |
| file-write          | src_ip          |         |          | &#10003;  |               |
|                     | access          | Legacy  |          | &#10003;  |               |

