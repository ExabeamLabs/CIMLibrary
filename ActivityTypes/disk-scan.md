disk-scan
=========

Description
-----------
A scan that targeted disk objecs took place

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | disk      |
| Activity      | scan      |
| Activity Type | disk-scan |
| Pretty Name   | Disk Scan |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#disk-scansuccess) or a [fail](#disk-scanfail).


disk-scan:success
-----------------

There are no fields for this activity type.


disk-scan:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |