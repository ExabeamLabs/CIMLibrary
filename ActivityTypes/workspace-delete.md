workspace-delete
================

Description
-----------
A workspace was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#workspace-deletesuccess) or a [fail](#workspace-deletefail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | workspace        |
| Activity      | delete           |
| Activity Type | workspace-delete |
| Pretty Name   | Workspace Delete |
| Legacy Name   |                  |

workspace-delete:success
------------------------

There are no fields for this activity type.


workspace-delete:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |