file-close
==========

Description
-----------
A file was closed

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-closesuccess) or a [fail](#file-closefail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | file       |
| Activity      | close      |
| Activity Type | file-close |
| Pretty Name   | File Close |
| Legacy Name   |            |

file-close:success
------------------

There are no fields for this activity type.


file-close:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |