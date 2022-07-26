endpoint-scan
=============

Description
-----------
A scan that targeted endpoints took place

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | endpoint      |
| Activity      | scan          |
| Activity Type | endpoint-scan |
| Pretty Name   | Endpoint Scan |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-scansuccess) or a [fail](#endpoint-scanfail).


endpoint-scan:success
---------------------

There are no fields for this activity type.


endpoint-scan:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |