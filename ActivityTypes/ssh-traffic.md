ssh-traffic
===========

Description
-----------
A representation of a single SSH packet

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | ssh         |
| Activity      | traffic     |
| Activity Type | ssh-traffic |
| Pretty Name   | Ssh Traffic |

Legacy Names
------------
| Success          | Fail |
| ---------------- | ---- |
| remote-logon<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ssh-trafficsuccess) or a [fail](#ssh-trafficfail).


ssh-traffic:success
-------------------

| Field            | Core | Detection | Informational |
| ---------------- | ---- | --------- | ------------- |
| tgs_service_name |      | &#10003;  |               |

A failure activity is not currently supported for this activity-type.