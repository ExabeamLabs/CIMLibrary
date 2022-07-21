disk-modify
===========

Description
-----------
The properties of a disk were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-modifysuccess) or a [fail](#disk-modifyfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | disk        |
| Activity      | modify      |
| Activity Type | disk-modify |
| Pretty Name   | Disk Modify |
| Legacy Name   |             |

disk-modify:success
-------------------

There are no fields for this activity type.


disk-modify:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |