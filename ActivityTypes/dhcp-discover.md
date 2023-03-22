dhcp-discover
=============

Description
-----------
A DHCP discover packet

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | dhcp          |
| Activity      | discover      |
| Activity Type | dhcp-discover |
| Pretty Name   | Dhcp Discover |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dhcp-discoversuccess) or a [fail](#dhcp-discoverfail).


dhcp-discover:success
---------------------

There are no fields for this activity type.


dhcp-discover:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |