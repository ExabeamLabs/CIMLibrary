file-download
=============

Description
-----------
A file was downloaded from a website

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | file          |
| Activity      | download      |
| Activity Type | file-download |
| Pretty Name   | File Download |

Legacy Names
------------
| Success           | Fail              |
| ----------------- | ----------------- |
| file-download<br> | file-download<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-downloadsuccess) or a [fail](#file-downloadfail).


file-download:success
---------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| file_url      |      | &#10003;  |               |
| src_file_name |      | &#10003;  |               |
| src_file_ext  |      | &#10003;  |               |
| src_file_dir  |      |           | &#10003;      |
| src_file_path |      | &#10003;  |               |
| cid           |      |           | &#10003;      |

file-download:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| file_url       |      | &#10003;  |               |
| src_file_name  |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| src_file_ext   |      | &#10003;  |               |
| src_file_dir   |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |
| src_file_path  |      | &#10003;  |               |
| cid            |      |           | &#10003;      |