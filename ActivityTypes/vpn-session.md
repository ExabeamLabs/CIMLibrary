vpn-session
===========

Description
-----------
A summary of a VPN network session

The possible fields for this activity type will vary depending on whether the activity was a [success](#vpn-sessionsuccess) or a [fail](#vpn-sessionfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | vpn         |
| Activity      | session     |
| Activity Type | vpn-session |
| Pretty Name   | Vpn Session |
| Legacy Name   |             |

vpn-session:success
-------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

vpn-session:fail
----------------

There are no fields for this activity type.
