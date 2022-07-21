endpoint-name-modify
====================

Description
-----------
The host name of an endpoint was changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-name-modifysuccess) or a [fail](#endpoint-name-modifyfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | endpoint             |
| Activity      | name-modify          |
| Activity Type | endpoint-name-modify |
| Pretty Name   | Endpoint Name Modify |
| Legacy Name   |                      |

endpoint-name-modify:success
----------------------------

There are no fields for this activity type.


endpoint-name-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |