file-move
=========

Description
-----------
A file was moved to another location

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-movesuccess) or a [fail](#file-movefail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | file      |
| Activity      | move      |
| Activity Type | file-move |
| Pretty Name   | File Move |
| Legacy Name   |           |

file-move:success
-----------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| src_file_name |      | &#10003;  |               |
| src_file_ext  |      | &#10003;  |               |
| src_file_dir  |      |           | &#10003;      |
| src_file_path |      | &#10003;  |               |

file-move:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| src_file_name  |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| src_file_ext   |      | &#10003;  |               |
| src_file_dir   |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |
| src_file_path  |      | &#10003;  |               |