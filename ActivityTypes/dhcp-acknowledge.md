dhcp-acknowledge
================

Description
-----------
A DHCP ack packet

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | dhcp             |
| Activity      | acknowledge      |
| Activity Type | dhcp-acknowledge |
| Pretty Name   | Dhcp Acknowledge |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dhcp-acknowledgesuccess) or a [fail](#dhcp-acknowledgefail).


dhcp-acknowledge:success
------------------------

There are no fields for this activity type.


dhcp-acknowledge:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |