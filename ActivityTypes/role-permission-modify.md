role-permission-modify
======================

Description
-----------
The permissions associated with a security role were changed

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | role                   |
| Activity      | permission-modify      |
| Activity Type | role-permission-modify |
| Pretty Name   | Role Permission Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-permission-modifysuccess) or a [fail](#role-permission-modifyfail).


role-permission-modify:success
------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |
| identities     |      | &#10003;  |               |

role-permission-modify:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| identities     |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |