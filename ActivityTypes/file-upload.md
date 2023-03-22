file-upload
===========

Description
-----------
A file was uploaded to a website

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | file        |
| Activity      | upload      |
| Activity Type | file-upload |
| Pretty Name   | File Upload |

Legacy Names
------------
| Success         | Fail            |
| --------------- | --------------- |
| file-upload<br> | file-upload<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-uploadsuccess) or a [fail](#file-uploadfail).


file-upload:success
-------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| file_url      |      | &#10003;  |               |
| src_file_name |      | &#10003;  |               |
| src_file_ext  |      | &#10003;  |               |
| src_file_dir  |      |           | &#10003;      |
| src_file_path |      | &#10003;  |               |

file-upload:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| file_url       |      | &#10003;  |               |
| src_file_name  |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| src_file_ext   |      | &#10003;  |               |
| src_file_dir   |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |
| src_file_path  |      | &#10003;  |               |