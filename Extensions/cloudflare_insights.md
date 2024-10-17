cloudflare insights
===================

Expression
----------

product = "cloudflare insights"

Fields
------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| src_ip             |      | &#10003;  |               |
| fallback_user_name |      |           |               |
| user               |      | &#10003;  |               |
| operation          |      |           | &#10003;      |

Activity Types
--------------

| Activity Type       | Field           | Status  | Core | Detection | Informational |
| ------------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-activity        | result          | Default |      |           | &#10003;      |
|                     | additional_info | Default |      |           | &#10003;      |
|                     | dest_ip         | Default |      | &#10003;  |               |
|                     | dest_host       | Default |      | &#10003;  |               |
|                     | src_host        | Default |      | &#10003;  |               |
| app-login           | additional_info | Default |      |           | &#10003;      |
| group-member-add    | additional_info |         |      |           |               |
| group-member-remove | additional_info |         |      |           |               |

