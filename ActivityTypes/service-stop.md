service-stop
============

Description
-----------
A service was stopped

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | service      |
| Activity      | stop         |
| Activity Type | service-stop |
| Pretty Name   | Service Stop |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#service-stopsuccess) or a [fail](#service-stopfail).


service-stop:success
--------------------

There are no fields for this activity type.


service-stop:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |