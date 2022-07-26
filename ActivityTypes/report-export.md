report-export
=============

Description
-----------
An export process for a report was initiated in the app

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | report        |
| Activity      | export        |
| Activity Type | report-export |
| Pretty Name   | Report Export |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#report-exportsuccess) or a [fail](#report-exportfail).


report-export:success
---------------------

There are no fields for this activity type.


report-export:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |