user-password-expire
====================

Description
-----------
A user accounts' password has expired

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | user                 |
| Activity      | password-expire      |
| Activity Type | user-password-expire |
| Pretty Name   | User Password Expire |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-password-expiresuccess) or a [fail](#user-password-expirefail).


user-password-expire:success
----------------------------

There are no fields for this activity type.


user-password-expire:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |