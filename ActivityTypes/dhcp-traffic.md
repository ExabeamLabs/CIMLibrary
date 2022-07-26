dhcp-traffic
============

Description
-----------
A representation of a single DHCP packet

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | dhcp         |
| Activity      | traffic      |
| Activity Type | dhcp-traffic |
| Pretty Name   | Dhcp Traffic |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dhcp-trafficsuccess) or a [fail](#dhcp-trafficfail).


dhcp-traffic:success
--------------------

There are no fields for this activity type.


dhcp-traffic:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |