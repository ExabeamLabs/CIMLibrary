pinsafe
=======

Expression
----------

product = "PINsafe"

Fields
------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| src_ip          |      |           | &#10003;      |
| additional_info |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field    | Status  | Core | Detection | Informational |
| ------------- | -------- | ------- | ---- | --------- | ------------- |
| app-activity  | app      | Default |      |           | &#10003;      |
|               | src_port | Default |      |           | &#10003;      |
|               | user     | Default |      | &#10003;  |               |
| app-login     |          |         |      |           |               |

