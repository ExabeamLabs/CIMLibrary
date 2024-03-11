silverfort authentication platform
==================================

Expression
----------

product = "silverfort"

Fields
------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| src_ip    |      |           | &#10003;      |
| dest_host |      |           | &#10003;      |
| src_host  |      |           | &#10003;      |

Activity Types
--------------

| Activity Type           | Field       | Status  | Core | Detection | Informational |
| ----------------------- | ----------- | ------- | ---- | --------- | ------------- |
| app-authentication      | auth_method | Default |      |           | &#10003;      |
|                         | dest_ip     | Default |      | &#10003;  |               |
| app-login               |             |         |      |           |               |
| endpoint-authentication | auth_method | Default |      |           | &#10003;      |
|                         | dest_ip     | Default |      | &#10003;  |               |

