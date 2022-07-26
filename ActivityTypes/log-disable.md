log-disable
===========

Description
-----------
The audit log generation from a log was disabled

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | log         |
| Activity      | disable     |
| Activity Type | log-disable |
| Pretty Name   | Log Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-disablesuccess) or a [fail](#log-disablefail).


log-disable:success
-------------------

There are no fields for this activity type.


log-disable:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |