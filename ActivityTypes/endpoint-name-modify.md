endpoint-name-modify
====================

Description
-----------
The host name of an endpoint was changed

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | endpoint             |
| Activity      | name-modify          |
| Activity Type | endpoint-name-modify |
| Pretty Name   | Endpoint Name Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-name-modifysuccess) or a [fail](#endpoint-name-modifyfail).


endpoint-name-modify:success
----------------------------

There are no fields for this activity type.


endpoint-name-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |