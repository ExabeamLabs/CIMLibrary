file-rename
===========

Description
-----------
A file was renamed

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-renamesuccess) or a [fail](#file-renamefail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | file        |
| Activity      | rename      |
| Activity Type | file-rename |
| Pretty Name   | File Rename |
| Legacy Name   |             |

file-rename:success
-------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| new_file_name |      |           | &#10003;      |
| old_file_name |      |           | &#10003;      |

file-rename:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| new_file_name  |      |           | &#10003;      |
| old_file_name  |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |