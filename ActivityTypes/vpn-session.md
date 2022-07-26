vpn-session
===========

Description
-----------
A summary of a VPN network session

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | vpn         |
| Activity      | session     |
| Activity Type | vpn-session |
| Pretty Name   | Vpn Session |

Legacy Names
------------
| Success            | Fail |
| ------------------ | ---- |
| vpn-connection<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vpn-sessionsuccess) or a [fail](#vpn-sessionfail).


vpn-session:success
-------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

A failure activity is not currently supported for this activity-type.