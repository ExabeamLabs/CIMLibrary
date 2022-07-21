mimecast secure email gateway
=============================

Expression
----------

product = "mimecast secure email gateway"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type | Field            | Status  | Core | Detection | Informational |
| ------------- | ---------------- | ------- | ---- | --------- | ------------- |
| app-activity  | src_ip           | Default |      | &#10003;  |               |
|               | application      | Default |      |           | &#10003;      |
|               | resource         | Default |      |           | &#10003;      |
|               | additional_info  | Default |      |           | &#10003;      |
|               | domain           | Default |      |           | &#10003;      |
|               | log_source       | Default |      |           | &#10003;      |
|               | user             | Default |      | &#10003;  |               |
|               | object           | Default |      |           | &#10003;      |
|               | target           | Default |      |           | &#10003;      |
| app-login     | src_ip           | Default |      | &#10003;  |               |
| email-read    | result           | Default |      |           | &#10003;      |
|               | email_address    | Default |      |           | &#10003;      |
|               | email_user       | Default |      |           | &#10003;      |
|               | application      | Default |      |           | &#10003;      |
|               | additional_info  | Default |      |           | &#10003;      |
|               | resource         | Default |      |           | &#10003;      |
|               | log_source       | Default |      |           | &#10003;      |
|               | dest_email       | Default |      |           | &#10003;      |
|               | email_domain     | Default |      |           | &#10003;      |
|               | operation        | Default |      |           | &#10003;      |
|               | object           | Default |      |           | &#10003;      |
| email-receive | src_ip           | Default |      | &#10003;  |               |
|               | bytes            | Default |      |           | &#10003;      |
|               | file_type        | Default |      |           | &#10003;      |
|               | hash_md5         | Default |      |           | &#10003;      |
|               | message_id       | Default |      |           | &#10003;      |
|               | spam_score       | Default |      |           | &#10003;      |
|               | attachment_count | Default |      |           | &#10003;      |
|               | direction        | Default |      |           | &#10003;      |
|               | attachment_size  | Default |      |           | &#10003;      |

