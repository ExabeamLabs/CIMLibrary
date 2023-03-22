unix sendmail
=============

Expression
----------

product = "unix sendmail"

Fields
------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| src_ip         |      |           | &#10003;      |
| protocol       |      |           | &#10003;      |
| return_path    |      |           | &#10003;      |
| bytes          |      |           | &#10003;      |
| alert_id       |      |           | &#10003;      |
| dest_ip        |      |           | &#10003;      |
| dest_host      |      |           | &#10003;      |
| bytes_unit     |      |           | &#10003;      |
| num_recipients |      |           | &#10003;      |

Activity Types
--------------

| Activity Type | Field | Status | Core | Detection | Informational |
| ------------- | ----- | ------ | ---- | --------- | ------------- |
| email-receive |       |        |      |           |               |
| email-send    |       |        |      |           |               |

