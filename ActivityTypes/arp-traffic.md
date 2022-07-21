arp-traffic
===========

Description
-----------
A representation of a single ARP packet

The possible fields for this activity type will vary depending on whether the activity was a [success](#arp-trafficsuccess) or a [fail](#arp-trafficfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | arp         |
| Activity      | traffic     |
| Activity Type | arp-traffic |
| Pretty Name   | Arp Traffic |
| Legacy Name   |             |

arp-traffic:success
-------------------

There are no fields for this activity type.


arp-traffic:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |