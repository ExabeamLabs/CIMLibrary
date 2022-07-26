radius-traffic
==============

Description
-----------
A representation of a single RADIUS packet

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | radius         |
| Activity      | traffic        |
| Activity Type | radius-traffic |
| Pretty Name   | Radius Traffic |

Legacy Names
------------
| Success       | Fail                 |
| ------------- | -------------------- |
| nac-logon<br> | nac-failed-logon<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#radius-trafficsuccess) or a [fail](#radius-trafficfail).


radius-traffic:success
----------------------

There are no fields for this activity type.


radius-traffic:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |