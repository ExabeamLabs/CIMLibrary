dashboard-download
==================

Description
-----------
A dashboard was downloaded

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | dashboard          |
| Activity      | download           |
| Activity Type | dashboard-download |
| Pretty Name   | Dashboard Download |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dashboard-downloadsuccess) or a [fail](#dashboard-downloadfail).


dashboard-download:success
--------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| file_ext  |      |           | &#10003;      |
| file_name |      |           | &#10003;      |

dashboard-download:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| file_ext       |      |           | &#10003;      |
| file_name      |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |