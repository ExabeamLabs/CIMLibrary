file-delete
===========

Description
-----------
A file was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-deletesuccess) or a [fail](#file-deletefail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | file        |
| Activity      | delete      |
| Activity Type | file-delete |
| Pretty Name   | File Delete |
| Legacy Name   |             |

file-delete:success
-------------------

There are no fields for this activity type.


file-delete:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |