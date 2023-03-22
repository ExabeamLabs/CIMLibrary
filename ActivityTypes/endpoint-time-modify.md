endpoint-time-modify
====================

Description
-----------
The internal time of an endpoint was changed

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | endpoint             |
| Activity      | time-modify          |
| Activity Type | endpoint-time-modify |
| Pretty Name   | Endpoint Time Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-time-modifysuccess) or a [fail](#endpoint-time-modifyfail).


endpoint-time-modify:success
----------------------------

There are no fields for this activity type.


endpoint-time-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |