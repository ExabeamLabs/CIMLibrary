certificate-request
===================

Description
-----------
A digital certificate enrollment or creation was requested by an entity

The possible fields for this activity type will vary depending on whether the activity was a [success](#certificate-requestsuccess) or a [fail](#certificate-requestfail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | certificate         |
| Activity      | request             |
| Activity Type | certificate-request |
| Pretty Name   | Certificate Request |
| Legacy Name   |                     |

certificate-request:success
---------------------------

There are no fields for this activity type.


certificate-request:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |