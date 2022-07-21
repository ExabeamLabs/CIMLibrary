role-assume
===========

Description
-----------
A security role identity was assumed by another identity, granting itself this roles' permissions.

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-assumesuccess) or a [fail](#role-assumefail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | role        |
| Activity      | assume      |
| Activity Type | role-assume |
| Pretty Name   | Role Assume |
| Legacy Name   |             |

role-assume:success
-------------------

There are no fields for this activity type.


role-assume:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |