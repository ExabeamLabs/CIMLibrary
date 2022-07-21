user-mfa-disable
================

Description
-----------
The MFA configuration for a user account was set to disabled

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-mfa-disablesuccess) or a [fail](#user-mfa-disablefail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | user             |
| Activity      | mfa-disable      |
| Activity Type | user-mfa-disable |
| Pretty Name   | User Mfa Disable |
| Legacy Name   |                  |

user-mfa-disable:success
------------------------

There are no fields for this activity type.


user-mfa-disable:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |