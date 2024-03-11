email-recipient-remove
======================

Description
-----------
A recipient was removed from an email message

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | email                  |
| Activity      | recipient-remove       |
| Activity Type | email-recipient-remove |
| Pretty Name   | Email Recipient Remove |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-recipient-removesuccess) or a [fail](#email-recipient-removefail).


email-recipient-remove:success
------------------------------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| dest_email_domain  |          |           | &#10003;      |
| dest_email_user    |          |           | &#10003;      |
| dest_email_address |          |           | &#10003;      |
| dest_domain        |          |           | &#10003;      |
| dest_user          |          |           | &#10003;      |
| src_email_address  | &#10003; |           |               |

email-recipient-remove:fail
---------------------------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| dest_email_domain  |          |           | &#10003;      |
| dest_email_user    |          |           | &#10003;      |
| failure_code       |          | &#10003;  |               |
| dest_email_address |          |           | &#10003;      |
| dest_domain        |          |           | &#10003;      |
| dest_user          |          |           | &#10003;      |
| src_email_address  | &#10003; |           |               |
| failure_reason     |          | &#10003;  |               |