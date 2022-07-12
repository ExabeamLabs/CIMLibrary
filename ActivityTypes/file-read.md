file-read
=========

Description
-----------
A file was opened/read

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-readsuccess) or a [fail](#file-readfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | file      |
| Activity      | read      |
| Activity Type | file-read |
| Pretty Name   | File Read |
| Legacy Name   |           |

file-read:success
-----------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| is_dok |      | &#10003;  |               |

file-read:fail
--------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| is_dok |      | &#10003;  |               |