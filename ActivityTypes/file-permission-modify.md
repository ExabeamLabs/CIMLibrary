file-permission-modify
======================

Description
-----------
The permissions that apply to a file were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-permission-modifysuccess) or a [fail](#file-permission-modifyfail).

| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | file                   |
| Activity      | permission-modify      |
| Activity Type | file-permission-modify |
| Pretty Name   | File Permission Modify |
| Legacy Name   |                        |

file-permission-modify:success
------------------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| permissions |      | &#10003;  |               |

file-permission-modify:fail
---------------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| permissions |      | &#10003;  |               |