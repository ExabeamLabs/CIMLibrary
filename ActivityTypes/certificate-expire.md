certificate-expire
==================

Description
-----------
A digital certificate has timed out and expired

The possible fields for this activity type will vary depending on whether the activity was a [success](#certificate-expiresuccess) or a [fail](#certificate-expirefail).

| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | certificate        |
| Activity      | expire             |
| Activity Type | certificate-expire |
| Pretty Name   | Certificate Expire |
| Legacy Name   |                    |

certificate-expire:success
--------------------------

There are no fields for this activity type.


certificate-expire:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |