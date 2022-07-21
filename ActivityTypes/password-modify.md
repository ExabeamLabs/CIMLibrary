password-modify
===============

Description
-----------
The value of a stored password was changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-modifysuccess) or a [fail](#password-modifyfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | password        |
| Activity      | modify          |
| Activity Type | password-modify |
| Pretty Name   | Password Modify |
| Legacy Name   |                 |

password-modify:success
-----------------------

There are no fields for this activity type.


password-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |