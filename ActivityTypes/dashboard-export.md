dashboard-export
================

Description
-----------
An export process for a dashboard was initiated

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | dashboard        |
| Activity      | export           |
| Activity Type | dashboard-export |
| Pretty Name   | Dashboard Export |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dashboard-exportsuccess) or a [fail](#dashboard-exportfail).


dashboard-export:success
------------------------

There are no fields for this activity type.


dashboard-export:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |