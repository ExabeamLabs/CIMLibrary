network-traffic
===============

Description
-----------
A representation of a single network packet

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | network         |
| Activity      | traffic         |
| Activity Type | network-traffic |
| Pretty Name   | Network Traffic |

Legacy Names
------------
| Success                                                 | Fail                                                |
| ------------------------------------------------------- | --------------------------------------------------- |
| netflow-connection<br>network-connection-successful<br> | netflow-connection<br>network-connection-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#network-trafficsuccess) or a [fail](#network-trafficfail).


network-traffic:success
-----------------------

There are no fields for this activity type.


network-traffic:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |