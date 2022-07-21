user-password-modify
====================

Description
-----------
A user accounts' password was changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-password-modifysuccess) or a [fail](#user-password-modifyfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | user                 |
| Activity      | password-modify      |
| Activity Type | user-password-modify |
| Pretty Name   | User Password Modify |
| Legacy Name   |                      |

user-password-modify:success
----------------------------

There are no fields for this activity type.


user-password-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |