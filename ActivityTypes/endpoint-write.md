endpoint-write
==============

Description
-----------
An endpoint object was created or modified, only used as a catch all if create or modify cannot be determined

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-writesuccess) or a [fail](#endpoint-writefail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | endpoint       |
| Activity      | write          |
| Activity Type | endpoint-write |
| Pretty Name   | Endpoint Write |
| Legacy Name   |                |

endpoint-write:success
----------------------

There are no fields for this activity type.


endpoint-write:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |