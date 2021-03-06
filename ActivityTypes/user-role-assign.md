user-role-assign
================

Description
-----------
A user account was assigned a security role

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | user             |
| Activity      | role-assign      |
| Activity Type | user-role-assign |
| Pretty Name   | User Role Assign |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-role-assignsuccess) or a [fail](#user-role-assignfail).


user-role-assign:success
------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |

user-role-assign:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| role_name      |      |           | &#10003;      |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |