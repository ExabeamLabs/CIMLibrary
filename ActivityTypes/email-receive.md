email-receive
=============

Description
-----------
A user received an email message

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | email         |
| Activity      | receive       |
| Activity Type | email-receive |
| Pretty Name   | Email Receive |

Legacy Names
------------
| Success                | Fail                          |
| ---------------------- | ----------------------------- |
| dlp-email-alert-in<br> | dlp-email-alert-in-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-receivesuccess) or a [fail](#email-receivefail).


email-receive:success
---------------------

| Field                 | Core     | Detection | Informational |
| --------------------- | -------- | --------- | ------------- |
| email_recipients      |          |           | &#10003;      |
| email_attachment      |          |           | &#10003;      |
| dest_email_user       |          |           | &#10003;      |
| dest_user_full_name   |          |           | &#10003;      |
| dest_user             | &#10003; |           |               |
| email_attachments     |          |           | &#10003;      |
| dest_email_domain     |          |           | &#10003;      |
| email_address         | &#10003; |           |               |
| file_ext              |          |           | &#10003;      |
| email_user            |          |           | &#10003;      |
| dest_domain_user_name |          |           |               |
| bytes                 |          | &#10003;  |               |
| dest_email_address    | &#10003; |           |               |
| dest_domain           |          |           | &#10003;      |
| email_domain          |          |           | &#10003;      |
| src_email_address     | &#10003; |           |               |
| src_email_domain      |          |           | &#10003;      |
| email_subject         |          |           | &#10003;      |
| user                  |          | &#10003;  |               |

email-receive:fail
------------------

| Field                 | Core     | Detection | Informational |
| --------------------- | -------- | --------- | ------------- |
| email_recipients      |          |           | &#10003;      |
| email_attachment      |          |           | &#10003;      |
| dest_email_user       |          |           | &#10003;      |
| failure_code          |          | &#10003;  |               |
| dest_user_full_name   |          |           | &#10003;      |
| dest_user             | &#10003; |           |               |
| failure_reason        |          | &#10003;  |               |
| email_attachments     |          |           | &#10003;      |
| dest_email_domain     |          |           | &#10003;      |
| email_address         | &#10003; |           |               |
| file_ext              |          |           | &#10003;      |
| email_user            |          |           | &#10003;      |
| dest_domain_user_name |          |           |               |
| bytes                 |          | &#10003;  |               |
| dest_email_address    | &#10003; |           |               |
| dest_domain           |          |           | &#10003;      |
| email_domain          |          |           | &#10003;      |
| src_email_address     | &#10003; |           |               |
| src_email_domain      |          |           | &#10003;      |
| email_subject         |          |           | &#10003;      |
| user                  |          | &#10003;  |               |