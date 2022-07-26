app-scan
========

Description
-----------
A scan that targeted apps took place

Parameters
----------
| Parameter     | Value    |
| ------------- | -------- |
| Subject       | app      |
| Activity      | scan     |
| Activity Type | app-scan |
| Pretty Name   | App Scan |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-scansuccess) or a [fail](#app-scanfail).


app-scan:success
----------------

There are no fields for this activity type.


app-scan:fail
-------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |