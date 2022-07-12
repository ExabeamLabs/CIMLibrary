email-recipient-add
===================

Description
-----------
A recipient was added to an email message

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-recipient-addsuccess) or a [fail](#email-recipient-addfail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | email               |
| Activity      | recipient-add       |
| Activity Type | email-recipient-add |
| Pretty Name   | Email Recipient Add |
| Legacy Name   |                     |

email-recipient-add:success
---------------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| dest_email_domain  |      |           | &#10003;      |
| dest_email_user    |      |           | &#10003;      |
| dest_email_address |      |           | &#10003;      |
| dest_domain        |      |           | &#10003;      |
| dest_user          |      |           | &#10003;      |

email-recipient-add:fail
------------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| dest_email_domain  |      |           | &#10003;      |
| dest_email_user    |      |           | &#10003;      |
| dest_email_address |      |           | &#10003;      |
| dest_domain        |      |           | &#10003;      |
| dest_user          |      |           | &#10003;      |