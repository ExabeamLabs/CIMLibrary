endpoint-start
==============

Description
-----------
An endpoint was booted up

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | endpoint       |
| Activity      | start          |
| Activity Type | endpoint-start |
| Pretty Name   | Endpoint Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-startsuccess) or a [fail](#endpoint-startfail).


endpoint-start:success
----------------------

There are no fields for this activity type.


endpoint-start:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |