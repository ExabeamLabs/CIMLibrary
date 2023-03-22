sap
===

Expression
----------

product = "sap"

Fields
------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| severity    |      |           | &#10003;      |
| src_ip      |      |           | &#10003;      |
| server      |      |           | &#10003;      |
| src_mac     |      |           | &#10003;      |
| activity_id |      |           | &#10003;      |
| user_sid    |      |           | &#10003;      |
| client      |      |           | &#10003;      |
| result_code |      |           | &#10003;      |
| category    |      |           | &#10003;      |
| aid         |      |           | &#10003;      |
| transaction |      |           | &#10003;      |
| object      |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field           | Status  | Core | Detection | Informational |
| ------------- | --------------- | ------- | ---- | --------- | ------------- |
| app-activity  |                 |         |      |           |               |
| app-login     | additional_info | Default |      |           | &#10003;      |
| file-download |                 |         |      |           |               |
| user-create   |                 |         |      |           |               |
| user-delete   |                 |         |      |           |               |
| user-lock     |                 |         |      |           |               |
| user-unlock   |                 |         |      |           |               |

