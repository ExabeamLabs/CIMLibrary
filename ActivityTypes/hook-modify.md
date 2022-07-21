hook-modify
===========

Description
-----------
The properties, configuration or content of a hook object were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#hook-modifysuccess) or a [fail](#hook-modifyfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | hook        |
| Activity      | modify      |
| Activity Type | hook-modify |
| Pretty Name   | Hook Modify |
| Legacy Name   |             |

hook-modify:success
-------------------

There are no fields for this activity type.


hook-modify:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |