user-mfa-enable
===============

Description
-----------
The MFA configuration for a user account was set to enabled

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | user            |
| Activity      | mfa-enable      |
| Activity Type | user-mfa-enable |
| Pretty Name   | User Mfa Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-mfa-enablesuccess) or a [fail](#user-mfa-enablefail).


user-mfa-enable:success
-----------------------

There are no fields for this activity type.


user-mfa-enable:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |