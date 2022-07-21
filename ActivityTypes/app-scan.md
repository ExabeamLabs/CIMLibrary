app-scan
========

Description
-----------
A scan that targeted apps took place

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-scansuccess) or a [fail](#app-scanfail).

| Parameter     | Value    |
| ------------- | -------- |
| Subject       | app      |
| Activity      | scan     |
| Activity Type | app-scan |
| Pretty Name   | App Scan |
| Legacy Name   |          |

app-scan:success
----------------

There are no fields for this activity type.


app-scan:fail
-------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |