microsoft exchange
==================

Expression
----------

product = "microsoft exchange"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type       | Field            | Status  | Core     | Detection | Informational |
| ------------------- | ---------------- | ------- | -------- | --------- | ------------- |
| alert-trigger       | result           |         |          |           |               |
|                     | sender           | Legacy  | &#10003; |           |               |
|                     | bytes            | Legacy  |          | &#10003;  |               |
|                     | recipients       |         |          |           |               |
|                     | dest_ip          | Legacy  | &#10003; | &#10003;  |               |
|                     | recipient        |         |          |           |               |
|                     | src_host         | Legacy  | &#10003; | &#10003;  |               |
|                     | email_subject    |         |          |           |               |
| app-login           | src_ip           | Default | &#10003; | &#10003;  |               |
|                     | protocol         | Default |          |           | &#10003;      |
|                     | bytes_out        | Default |          |           | &#10003;      |
|                     | bytes_in         | Default |          |           | &#10003;      |
|                     | dest_ip          | Default |          | &#10003;  |               |
|                     | user_agent       | Default |          |           | &#10003;      |
| email-receive       | src_ip           | Default |          | &#10003;  |               |
|                     | external_address | Default |          |           | &#10003;      |
|                     | return_path      | Default |          |           | &#10003;      |
|                     | event_code       | Default |          |           | &#10003;      |
|                     | bytes            | Default |          |           | &#10003;      |
|                     | dest_ip          | Default |          | &#10003;  |               |
|                     | log_source       | Default |          |           | &#10003;      |
|                     | dest_host        | Default |          | &#10003;  |               |
|                     | traffic_type     | Default |          |           | &#10003;      |
|                     | src_host         | Default |          | &#10003;  |               |
|                     | direction        | Default |          |           | &#10003;      |
| email-send          | traffic_type     | Default |          |           | &#10003;      |
|                     | src_host         | Default |          | &#10003;  |               |
|                     | src_ip           | Default |          | &#10003;  |               |
|                     | src_port         | Default |          |           | &#10003;      |
|                     | return_path      | Default |          |           | &#10003;      |
|                     | event_code       | Default |          |           | &#10003;      |
|                     | bytes            | Default |          |           | &#10003;      |
|                     | process_name     | Default |          |           | &#10003;      |
|                     | dest_ip          | Default |          | &#10003;  |               |
|                     | log_source       | Default |          |           | &#10003;      |
|                     | user_sid         | Default |          |           | &#10003;      |
|                     | dest_host        | Default |          | &#10003;  |               |
|                     | direction        | Default |          |           | &#10003;      |
| mailbox-create      | email_address    | Default |          |           | &#10003;      |
|                     | email_user       | Default |          |           | &#10003;      |
|                     | application      | Default |          |           | &#10003;      |
|                     | email_domain     | Default |          |           | &#10003;      |
|                     | operation        | Default |          |           | &#10003;      |
| mailbox-item-create | email_address    | Default |          |           | &#10003;      |
|                     | email_user       | Default |          |           | &#10003;      |
|                     | application      | Default |          |           | &#10003;      |
|                     | email_domain     | Default |          |           | &#10003;      |
|                     | operation        | Default |          |           | &#10003;      |
| mailbox-item-delete | src_ip           | Default |          | &#10003;  |               |
|                     | email_address    | Default |          |           | &#10003;      |
|                     | application      | Default |          |           | &#10003;      |
|                     | email_user       | Default |          |           | &#10003;      |
|                     | additional_info  | Default |          |           | &#10003;      |
|                     | email_domain     | Default |          |           | &#10003;      |
|                     | user             | Default |          | &#10003;  |               |
|                     | operation        | Default |          |           | &#10003;      |
|                     | object           | Default |          |           | &#10003;      |
| mailbox-item-modify | email_address    | Default |          |           | &#10003;      |
|                     | email_user       | Default |          |           | &#10003;      |
|                     | application      | Default |          |           | &#10003;      |
|                     | email_domain     | Default |          |           | &#10003;      |
|                     | operation        | Default |          |           | &#10003;      |
| mailbox-modify      | email_address    | Default |          |           | &#10003;      |
|                     | email_user       | Default |          |           | &#10003;      |
|                     | application      | Default |          |           | &#10003;      |
|                     | email_domain     | Default |          |           | &#10003;      |
|                     | operation        | Default |          |           | &#10003;      |
| user-modify         | email_address    |         |          |           |               |
|                     | email_user       |         |          |           |               |
|                     | application      |         |          |           |               |
|                     | email_domain     |         |          |           |               |
|                     | operation        |         |          |           |               |

