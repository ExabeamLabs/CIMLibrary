email-send
==========

Description
-----------
A user sent an email message

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | email      |
| Activity      | send       |
| Activity Type | email-send |
| Pretty Name   | Email Send |

Legacy Names
------------
| Success                 | Fail                           |
| ----------------------- | ------------------------------ |
| dlp-email-alert-out<br> | dlp-email-alert-out-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-sendsuccess) or a [fail](#email-sendfail).


email-send:success
------------------

| Field                 | Core     | Detection | Informational |
| --------------------- | -------- | --------- | ------------- |
| email_recipients      |          |           | &#10003;      |
| email_attachment      |          |           | &#10003;      |
| dest_email_user       |          |           | &#10003;      |
| dest_user_full_name   |          |           | &#10003;      |
| file_name             |          | &#10003;  |               |
| dest_user             | &#10003; |           |               |
| email_attachments     |          |           | &#10003;      |
| num_recipients        |          | &#10003;  |               |
| dest_email_domain     |          |           | &#10003;      |
| email_address         | &#10003; |           |               |
| file_ext              |          | &#10003;  | &#10003;      |
| email_user            |          |           | &#10003;      |
| attachment            |          | &#10003;  |               |
| dest_domain_user_name |          |           |               |
| bytes                 |          | &#10003;  |               |
| dest_email_address    | &#10003; |           |               |
| dest_ip               |          | &#10003;  |               |
| dest_domain           |          |           | &#10003;      |
| email_domain          |          |           | &#10003;      |
| src_email_address     | &#10003; |           |               |
| src_email_domain      |          |           | &#10003;      |
| email_subject         |          | &#10003;  | &#10003;      |
| user                  |          | &#10003;  |               |

email-send:fail
---------------

| Field                 | Core     | Detection | Informational |
| --------------------- | -------- | --------- | ------------- |
| dest_email_user       |          |           | &#10003;      |
| dest_email_domain     |          |           | &#10003;      |
| email_user            |          |           | &#10003;      |
| attachment            |          | &#10003;  |               |
| dest_domain_user_name |          |           |               |
| dest_email_address    | &#10003; |           |               |
| src_email_domain      |          |           | &#10003;      |
| email_recipients      |          |           | &#10003;      |
| email_attachment      |          |           | &#10003;      |
| failure_code          |          | &#10003;  |               |
| dest_user_full_name   |          |           | &#10003;      |
| file_name             |          | &#10003;  |               |
| dest_user             | &#10003; |           |               |
| failure_reason        |          | &#10003;  |               |
| email_attachments     |          |           | &#10003;      |
| num_recipients        |          | &#10003;  |               |
| email_address         | &#10003; |           |               |
| file_ext              |          | &#10003;  | &#10003;      |
| bytes                 |          | &#10003;  |               |
| dest_ip               |          | &#10003;  |               |
| dest_domain           |          |           | &#10003;      |
| email_domain          |          |           | &#10003;      |
| src_email_address     | &#10003; |           |               |
| email_subject         |          | &#10003;  | &#10003;      |
| user                  |          | &#10003;  |               |