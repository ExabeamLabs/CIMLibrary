http-traffic
============

Description
-----------
A representation of a single HTTP packet

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | http         |
| Activity      | traffic      |
| Activity Type | http-traffic |
| Pretty Name   | Http Traffic |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#http-trafficsuccess) or a [fail](#http-trafficfail).


http-traffic:success
--------------------

There are no fields for this activity type.


http-traffic:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |