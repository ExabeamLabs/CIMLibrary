password-modify
===============

Description
-----------
The value of a stored password was changed

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | password        |
| Activity      | modify          |
| Activity Type | password-modify |
| Pretty Name   | Password Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-modifysuccess) or a [fail](#password-modifyfail).


password-modify:success
-----------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| local_user_name |      |           |               |

password-modify:fail
--------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| local_user_name |      |           |               |
| failure_reason  |      | &#10003;  |               |