user-role-revoke
================

Description
-----------
A user account was revoked a security role

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-role-revokesuccess) or a [fail](#user-role-revokefail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | user             |
| Activity      | role-revoke      |
| Activity Type | user-role-revoke |
| Pretty Name   | User Role Revoke |
| Legacy Name   |                  |

user-role-revoke:success
------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |

user-role-revoke:fail
---------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |