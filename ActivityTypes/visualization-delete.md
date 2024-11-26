visualization-delete
====================

Description
-----------
A visualization was deleted 

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | report               |
| Activity      | delete               |
| Activity Type | visualization-delete |
| Pretty Name   | Visualization Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#visualization-deletesuccess) or a [fail](#visualization-deletefail).


visualization-delete:success
----------------------------

There are no fields for this activity type.


visualization-delete:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |