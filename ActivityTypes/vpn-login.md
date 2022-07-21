vpn-login
=========

Description
-----------
A user logged in to a VPN

The possible fields for this activity type will vary depending on whether the activity was a [success](#vpn-loginsuccess) or a [fail](#vpn-loginfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | vpn       |
| Activity      | login     |
| Activity Type | vpn-login |
| Pretty Name   | Vpn Login |
| Legacy Name   |           |

vpn-login:success
-----------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

vpn-login:fail
--------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| domain         |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| user           | &#10003; | &#10003;  |               |