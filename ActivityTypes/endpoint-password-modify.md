endpoint-password-modify
========================

Description
-----------
The endpoint domain object associated password was updated

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-password-modifysuccess) or a [fail](#endpoint-password-modifyfail).

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | endpoint                 |
| Activity      | password-modify          |
| Activity Type | endpoint-password-modify |
| Pretty Name   | Endpoint Password Modify |
| Legacy Name   |                          |

endpoint-password-modify:success
--------------------------------

There are no fields for this activity type.


endpoint-password-modify:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |