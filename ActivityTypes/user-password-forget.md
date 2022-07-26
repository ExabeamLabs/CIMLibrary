user-password-forget
====================

Description
-----------
A user has initiated a 'forgot password' process

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | user                 |
| Activity      | password-forget      |
| Activity Type | user-password-forget |
| Pretty Name   | User Password Forget |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-password-forgetsuccess) or a [fail](#user-password-forgetfail).


user-password-forget:success
----------------------------

There are no fields for this activity type.


user-password-forget:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |