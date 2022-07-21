group-role-revoke
=================

Description
-----------
A group object was revoked a security role

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-role-revokesuccess) or a [fail](#group-role-revokefail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | group             |
| Activity      | role-revoke       |
| Activity Type | group-role-revoke |
| Pretty Name   | Group Role Revoke |
| Legacy Name   |                   |

group-role-revoke:success
-------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |

group-role-revoke:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| role_name      |      |           | &#10003;      |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |