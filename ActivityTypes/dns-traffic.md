dns-traffic
===========

Description
-----------
A representation of a single DNS packet

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | dns         |
| Activity      | traffic     |
| Activity Type | dns-traffic |
| Pretty Name   | Dns Traffic |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dns-trafficsuccess) or a [fail](#dns-trafficfail).


dns-traffic:success
-------------------

| Field                 | Core | Detection | Informational |
| --------------------- | ---- | --------- | ------------- |
| dest_external_country |      | &#10003;  |               |

dns-traffic:fail
----------------

| Field                 | Core | Detection | Informational |
| --------------------- | ---- | --------- | ------------- |
| failure_code          |      | &#10003;  |               |
| dest_external_country |      | &#10003;  |               |
| failure_reason        |      | &#10003;  |               |