vpn-authentication
==================

Description
-----------
A part of an identification process to a VPN that is not the login

The possible fields for this activity type will vary depending on whether the activity was a [success](#vpn-authenticationsuccess) or a [fail](#vpn-authenticationfail).

| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | vpn                |
| Activity      | authentication     |
| Activity Type | vpn-authentication |
| Pretty Name   | Vpn Authentication |
| Legacy Name   |                    |

vpn-authentication:success
--------------------------

| Field               | Core     | Detection | Informational |
| ------------------- | -------- | --------- | ------------- |
| domain              |          | &#10003;  |               |
| user                | &#10003; | &#10003;  |               |
| authentication_type | &#10003; | &#10003;  |               |

vpn-authentication:fail
-----------------------

There are no fields for this activity type.
