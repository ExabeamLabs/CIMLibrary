endpoint-stop
=============

Description
-----------
An endpoint was shutdown

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | endpoint      |
| Activity      | stop          |
| Activity Type | endpoint-stop |
| Pretty Name   | Endpoint Stop |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-stopsuccess) or a [fail](#endpoint-stopfail).


endpoint-stop:success
---------------------

There are no fields for this activity type.


endpoint-stop:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |