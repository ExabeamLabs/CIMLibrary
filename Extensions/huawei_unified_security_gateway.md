huawei unified security gateway
===============================

Expression
----------

product = huawei unified security gateway

Fields
------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| src_ip |      |           | &#10003;      |

Activity Types
--------------

| Activity Type  | Field               | Status  | Core     | Detection | Informational |
| -------------- | ------------------- | ------- | -------- | --------- | ------------- |
| alert-trigger  | app                 |         |          |           |               |
|                | src_ip              | Legacy  | &#10003; | &#10003;  |               |
|                | src_port            | Legacy  |          |           | &#10003;      |
|                | protocol            | Legacy  |          | &#10003;  |               |
|                | email_address       |         |          |           |               |
|                | dest_ip             | Legacy  | &#10003; | &#10003;  |               |
|                | user                | Legacy  |          | &#10003;  |               |
|                | dest_port           | Legacy  |          | &#10003;  |               |
|                | policy              |         |          |           |               |
| app-login      |                     |         |          |           |               |
| process-create | user                | Default |          | &#10003;  |               |
| vpn-login      | src_port            | Default |          |           | &#10003;      |
|                | src_translated_ip   | Default |          |           | &#10003;      |
|                | protocol            | Default |          |           | &#10003;      |
|                | dest_ip             | Default |          | &#10003;  |               |
|                | src_translated_port | Default |          |           | &#10003;      |
|                | dest_port           | Default |          |           | &#10003;      |

