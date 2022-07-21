ssl-traffic
===========

Description
-----------
A representation of a single SSL packet

The possible fields for this activity type will vary depending on whether the activity was a [success](#ssl-trafficsuccess) or a [fail](#ssl-trafficfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | ssl         |
| Activity      | traffic     |
| Activity Type | ssl-traffic |
| Pretty Name   | Ssl Traffic |
| Legacy Name   |             |

ssl-traffic:success
-------------------

There are no fields for this activity type.


ssl-traffic:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |