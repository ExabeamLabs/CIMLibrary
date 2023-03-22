user-role-modify
================

Description
-----------
The security role association of a user account was modified directly

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | user             |
| Activity      | role-modify      |
| Activity Type | user-role-modify |
| Pretty Name   | User Role Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-role-modifysuccess) or a [fail](#user-role-modifyfail).


user-role-modify:success
------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |

user-role-modify:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| role_name      |      |           | &#10003;      |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |