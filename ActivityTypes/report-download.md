report-download
===============

Description
-----------
A report was downloaded from an app

The possible fields for this activity type will vary depending on whether the activity was a [success](#report-downloadsuccess) or a [fail](#report-downloadfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | report          |
| Activity      | download        |
| Activity Type | report-download |
| Pretty Name   | Report Download |
| Legacy Name   |                 |

report-download:success
-----------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| file_ext  |      |           | &#10003;      |
| file_name |      |           | &#10003;      |

report-download:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| file_ext       |      |           | &#10003;      |
| file_name      |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |