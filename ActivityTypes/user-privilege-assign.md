user-privilege-assign
=====================

Description
-----------
Privillege assigned to a user

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | user                  |
| Activity      | privilege-assign      |
| Activity Type | user-privilege-assign |
| Pretty Name   | User Privilege Assign |

Legacy Names
------------
| Success               | Fail                  |
| --------------------- | --------------------- |
| privileged-access<br> | privileged-access<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-privilege-assignsuccess) or a [fail](#user-privilege-assignfail).


user-privilege-assign:success
-----------------------------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| privileges |      |           |               |

user-privilege-assign:fail
--------------------------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| privileges |      |           |               |