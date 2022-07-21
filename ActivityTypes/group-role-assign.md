group-role-assign
=================

Description
-----------
A group object was assigned a security role

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-role-assignsuccess) or a [fail](#group-role-assignfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | group             |
| Activity      | role-assign       |
| Activity Type | group-role-assign |
| Pretty Name   | Group Role Assign |
| Legacy Name   |                   |

group-role-assign:success
-------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |

group-role-assign:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| role_name      |      |           | &#10003;      |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |