password-checkin
================

Description
-----------
A password was checked in from a vault, finishing the checkout process. a checkout is a one timed access of a password, that blocks other users from accessing it at that time

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-checkinsuccess) or a [fail](#password-checkinfail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | password         |
| Activity      | checkin          |
| Activity Type | password-checkin |
| Pretty Name   | Password Checkin |
| Legacy Name   |                  |

password-checkin:success
------------------------

There are no fields for this activity type.


password-checkin:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |