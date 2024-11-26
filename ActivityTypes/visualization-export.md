visualization-export
====================

Description
-----------
An export process for a visualization was initiated

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | visualization        |
| Activity      | export               |
| Activity Type | visualization-export |
| Pretty Name   | Visualization Export |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#visualization-exportsuccess) or a [fail](#visualization-exportfail).


visualization-export:success
----------------------------

There are no fields for this activity type.


visualization-export:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |