password-checkin
================

Description
-----------
A password was checked in from a vault, finishing the checkout process. a checkout is a one timed access of a password, that blocks other users from accessing it at that time

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | password         |
| Activity      | checkin          |
| Activity Type | password-checkin |
| Pretty Name   | Password Checkin |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-checkinsuccess) or a [fail](#password-checkinfail).


password-checkin:success
------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| local_user_name |      |           |               |

password-checkin:fail
---------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| local_user_name |      |           |               |
| failure_reason  |      | &#10003;  |               |