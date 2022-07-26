vpn-logout
==========

Description
-----------
A user logged out from a VPN

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | vpn        |
| Activity      | logout     |
| Activity Type | vpn-logout |
| Pretty Name   | Vpn Logout |

Legacy Names
------------
| Success        | Fail           |
| -------------- | -------------- |
| vpn-logout<br> | vpn-logout<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vpn-logoutsuccess) or a [fail](#vpn-logoutfail).


vpn-logout:success
------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

vpn-logout:fail
---------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| domain         |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| user           | &#10003; | &#10003;  |               |