user-password-reset
===================

Description
-----------
A user accounts' password was reset

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-password-resetsuccess) or a [fail](#user-password-resetfail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | user                |
| Activity      | password-reset      |
| Activity Type | user-password-reset |
| Pretty Name   | User Password Reset |
| Legacy Name   |                     |

user-password-reset:success
---------------------------

There are no fields for this activity type.


user-password-reset:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |