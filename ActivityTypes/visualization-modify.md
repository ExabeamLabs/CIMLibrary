visualization-modify
====================

Description
-----------
A request to modify a visualization was made

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | visualization        |
| Activity      | modify               |
| Activity Type | visualization-modify |
| Pretty Name   | Visualization Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#visualization-modifysuccess) or a [fail](#visualization-modifyfail).


visualization-modify:success
----------------------------

There are no fields for this activity type.


visualization-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |