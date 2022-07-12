user-role-assign
================

Description
-----------
A user account was assigned a security role

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-role-assignsuccess) or a [fail](#user-role-assignfail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | user             |
| Activity      | role-assign      |
| Activity Type | user-role-assign |
| Pretty Name   | User Role Assign |
| Legacy Name   |                  |

user-role-assign:success
------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |

user-role-assign:fail
---------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |