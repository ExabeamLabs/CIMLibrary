group-permission-modify
=======================

Description
-----------
The permissions of a group were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-permission-modifysuccess) or a [fail](#group-permission-modifyfail).

| Parameter     | Value                   |
| ------------- | ----------------------- |
| Subject       | group                   |
| Activity      | permission-modify       |
| Activity Type | group-permission-modify |
| Pretty Name   | Group Permission Modify |
| Legacy Name   |                         |

group-permission-modify:success
-------------------------------

There are no fields for this activity type.


group-permission-modify:fail
----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |