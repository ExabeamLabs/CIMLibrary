email-receive
=============

Description
-----------
A user received an email message

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-receivesuccess) or a [fail](#email-receivefail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | email         |
| Activity      | receive       |
| Activity Type | email-receive |
| Pretty Name   | Email Receive |
| Legacy Name   |               |

email-receive:success
---------------------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| email_recipients   |          |           | &#10003;      |
| email_attachment   |          |           | &#10003;      |
| dest_email_user    |          |           | &#10003;      |
| dest_user          | &#10003; |           |               |
| email_attachments  |          |           | &#10003;      |
| dest_email_domain  |          |           | &#10003;      |
| email_address      | &#10003; |           |               |
| file_ext           |          |           | &#10003;      |
| email_user         |          |           | &#10003;      |
| dest_email_address | &#10003; |           |               |
| dest_domain        |          |           | &#10003;      |
| email_domain       |          |           | &#10003;      |
| email_subject      |          |           | &#10003;      |

email-receive:fail
------------------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| email_recipients   |          |           | &#10003;      |
| email_attachment   |          |           | &#10003;      |
| dest_email_user    |          |           | &#10003;      |
| dest_user          | &#10003; |           |               |
| email_attachments  |          |           | &#10003;      |
| dest_email_domain  |          |           | &#10003;      |
| email_address      | &#10003; |           |               |
| file_ext           |          |           | &#10003;      |
| email_user         |          |           | &#10003;      |
| dest_email_address | &#10003; |           |               |
| dest_domain        |          |           | &#10003;      |
| email_domain       |          |           | &#10003;      |
| email_subject      |          |           | &#10003;      |