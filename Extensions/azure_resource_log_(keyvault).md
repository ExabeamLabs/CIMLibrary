azure resource log (keyvault)
=============================

Expression
----------

product = "azure resource log (keyvault)"

Fields
------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| tenant_id         |      |           | &#10003;      |
| operation_version |      |           | &#10003;      |
| operation_type    |      |           | &#10003;      |
| resource          |      |           | &#10003;      |
| service_name      |      | &#10003;  |               |
| event_category    |      |           | &#10003;      |
| creds_path        |      |           | &#10003;      |
| url               |      |           | &#10003;      |
| subscription_id   |      |           | &#10003;      |
| key_name          |      |           | &#10003;      |
| resource_group    |      |           | &#10003;      |
| creds_name        |      |           | &#10003;      |
| resource_path     |      |           | &#10003;      |
| correlation_id    |      |           | &#10003;      |
| result_code       |      |           | &#10003;      |
| resource_name     |      |           | &#10003;      |
| operation         |      | &#10003;  |               |
| user              |      | &#10003;  |               |
| user_agent        |      | &#10003;  |               |

Activity Types
--------------

| Activity Type | Field | Status | Core | Detection | Informational |
| ------------- | ----- | ------ | ---- | --------- | ------------- |
| key-read      |       |        |      |           |               |
| key-write     |       |        |      |           |               |

