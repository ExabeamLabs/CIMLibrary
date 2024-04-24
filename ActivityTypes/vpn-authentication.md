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
| Success                       | Fail                      |
| ----------------------------- | ------------------------- |
| authentication-successful<br> | authentication-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#vpn-authenticationsuccess) or a [fail](#vpn-authenticationfail).


vpn-authentication:success
--------------------------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| auth_type        | &#10003; | &#10003;  |               |
| domain           |          | &#10003;  |               |
| mfa_country      |          | &#10003;  |               |
| domain_user_name |          |           |               |
| mfa_device       |          | &#10003;  |               |
| user             | &#10003; | &#10003;  |               |

vpn-authentication:fail
-----------------------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| auth_type        | &#10003; | &#10003;  |               |
| failure_code     |          | &#10003;  |               |
| domain           |          | &#10003;  |               |
| mfa_country      |          | &#10003;  |               |
| domain_user_name |          |           |               |
| failure_reason   |          | &#10003;  |               |
| mfa_device       |          | &#10003;  |               |
| user             | &#10003; | &#10003;  |               |