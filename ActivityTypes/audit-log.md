audit-log
=========

Description
-----------
An audit log entry was created on a security product or program

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | audit     |
| Activity      | log       |
| Activity Type | audit-log |
| Pretty Name   | Audit Log |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#audit-logsuccess) or a [fail](#audit-logfail).


audit-log:success
-----------------

There are no fields for this activity type.


audit-log:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |