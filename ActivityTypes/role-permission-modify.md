role-permission-modify
======================

Description
-----------
The permissions associated with a security role were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#role-permission-modifysuccess) or a [fail](#role-permission-modifyfail).

| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | role                   |
| Activity      | permission-modify      |
| Activity Type | role-permission-modify |
| Pretty Name   | Role Permission Modify |
| Legacy Name   |                        |

role-permission-modify:success
------------------------------

There are no fields for this activity type.


role-permission-modify:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |