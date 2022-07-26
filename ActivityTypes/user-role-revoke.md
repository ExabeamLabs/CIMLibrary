user-role-revoke
================

Description
-----------
A user account was revoked a security role

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | user             |
| Activity      | role-revoke      |
| Activity Type | user-role-revoke |
| Pretty Name   | User Role Revoke |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-role-revokesuccess) or a [fail](#user-role-revokefail).


user-role-revoke:success
------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |

user-role-revoke:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| role_name      |      |           | &#10003;      |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |