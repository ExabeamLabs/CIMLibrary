vpn-authentication
==================

Description
-----------
A part of an identification process to a VPN that is not the login

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | vpn                |
| Activity      | authentication     |
| Activity Type | vpn-authentication |
| Pretty Name   | Vpn Authentication |

Legacy Names
------------
| Success                       | Fail |
| ----------------------------- | ---- |
| authentication-successful<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vpn-authenticationsuccess) or a [fail](#vpn-authenticationfail).


vpn-authentication:success
--------------------------

| Field               | Core     | Detection | Informational |
| ------------------- | -------- | --------- | ------------- |
| domain              |          | &#10003;  |               |
| user                | &#10003; | &#10003;  |               |
| authentication_type | &#10003; | &#10003;  |               |

A failure activity is not currently supported for this activity-type.