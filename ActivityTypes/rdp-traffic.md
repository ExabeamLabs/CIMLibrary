rdp-traffic
===========

Description
-----------
A representation of a single RDP packet

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | rdp         |
| Activity      | traffic     |
| Activity Type | rdp-traffic |
| Pretty Name   | Rdp Traffic |

Legacy Names
------------
| Success          | Fail |
| ---------------- | ---- |
| remote-logon<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#rdp-trafficsuccess) or a [fail](#rdp-trafficfail).


rdp-traffic:success
-------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| tgs_service_name |      | &#10003;  |               |

A failure activity is not currently supported for this activity-type.