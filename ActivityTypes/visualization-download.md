visualization-download
======================

Description
-----------
A visualization was downloaded

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | visualization          |
| Activity      | download               |
| Activity Type | visualization-download |
| Pretty Name   | Visualization Download |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#visualization-downloadsuccess) or a [fail](#visualization-downloadfail).


visualization-download:success
------------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| file_ext  |      |           | &#10003;      |
| file_name |      |           | &#10003;      |

visualization-download:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| file_ext       |      |           | &#10003;      |
| file_name      |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |