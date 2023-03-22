log-enable
==========

Description
-----------
The audit log generation from a log was enabled

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | log        |
| Activity      | enable     |
| Activity Type | log-enable |
| Pretty Name   | Log Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-enablesuccess) or a [fail](#log-enablefail).


log-enable:success
------------------

There are no fields for this activity type.


log-enable:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |