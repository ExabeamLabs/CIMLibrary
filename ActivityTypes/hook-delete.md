hook-delete
===========

Description
-----------
A hook object was deleted or removed

The possible fields for this activity type will vary depending on whether the activity was a [success](#hook-deletesuccess) or a [fail](#hook-deletefail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | hook        |
| Activity      | delete      |
| Activity Type | hook-delete |
| Pretty Name   | Hook Delete |
| Legacy Name   |             |

hook-delete:success
-------------------

There are no fields for this activity type.


hook-delete:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |