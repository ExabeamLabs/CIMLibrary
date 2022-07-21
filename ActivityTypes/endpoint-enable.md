endpoint-enable
===============

Description
-----------
An endpoint was enabled and is ready for use

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-enablesuccess) or a [fail](#endpoint-enablefail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | endpoint        |
| Activity      | enable          |
| Activity Type | endpoint-enable |
| Pretty Name   | Endpoint Enable |
| Legacy Name   |                 |

endpoint-enable:success
-----------------------

There are no fields for this activity type.


endpoint-enable:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |