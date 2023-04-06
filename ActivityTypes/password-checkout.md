password-checkout
=================

Description
-----------
A password was checked out from a vault, a checkout is a one timed access of a password, that blocks other users from accessing it at that time

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | password          |
| Activity      | checkout          |
| Activity Type | password-checkout |
| Pretty Name   | Password Checkout |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-checkoutsuccess) or a [fail](#password-checkoutfail).


password-checkout:success
-------------------------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| src_host   |      | &#10003;  |               |
| safe_value |      | &#10003;  |               |

password-checkout:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| src_host       |      | &#10003;  |               |
| safe_value     |      | &#10003;  |               |