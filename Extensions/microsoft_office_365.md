microsoft office 365
====================

Expression
----------

product = microsoft office 365

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type | Field                 | Status  | Core     | Detection | Informational |
| ------------- | --------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger | additional_info       |         |          |           |               |
|               | alert_id              | Legacy  |          |           | &#10003;      |
|               | dest_ip               | Legacy  | &#10003; | &#10003;  |               |
|               | domain                |         |          |           |               |
|               | dest_host             | Legacy  |          | &#10003;  |               |
|               | domain_user_name      |         |          |           |               |
|               | src_host              | Legacy  | &#10003; | &#10003;  |               |
|               | user                  | Legacy  |          | &#10003;  |               |
| app-activity  | sensitivity_label     | Default |          |           | &#10003;      |
|               | encrypted             | Default |          |           | &#10003;      |
|               | old_sensitivity_label | Default |          |           | &#10003;      |
|               | label_id              | Default |          |           | &#10003;      |
| email-receive | connectors            |         |          |           |               |
|               | dkim_result           |         |          |           |               |
|               | spf_result            |         |          |           |               |
|               | dmarc_result          |         |          |           |               |
|               | compauth_result       |         |          |           |               |
| email-send    | connectors            |         |          |           |               |
|               | dkim_result           |         |          |           |               |
|               | spf_result            |         |          |           |               |
|               | dmarc_result          |         |          |           |               |
|               | compauth_result       |         |          |           |               |

