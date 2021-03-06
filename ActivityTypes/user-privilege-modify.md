user-privilege-modify
=====================

Description
-----------
A user privilege was modified

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | user                  |
| Activity      | privilege-modify      |
| Activity Type | user-privilege-modify |
| Pretty Name   | User Privilege Modify |

Legacy Names
------------
| Success               | Fail                  |
| --------------------- | --------------------- |
| privileged-access<br> | privileged-access<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-privilege-modifysuccess) or a [fail](#user-privilege-modifyfail).


user-privilege-modify:success
-----------------------------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| privileges |      |           |               |

user-privilege-modify:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| privileges     |      |           |               |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |