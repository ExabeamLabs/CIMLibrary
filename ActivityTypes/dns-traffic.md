dns-traffic
===========

Description
-----------
A representation of a single DNS packet

The possible fields for this activity type will vary depending on whether the activity was a [success](#dns-trafficsuccess) or a [fail](#dns-trafficfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | dns         |
| Activity      | traffic     |
| Activity Type | dns-traffic |
| Pretty Name   | Dns Traffic |
| Legacy Name   |             |

dns-traffic:success
-------------------

There are no fields for this activity type.


dns-traffic:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |