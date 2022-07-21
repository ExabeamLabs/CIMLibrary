log_source-remove
=================

Description
-----------
A log source was deleted from a program or an app

The possible fields for this activity type will vary depending on whether the activity was a [success](#log_source-removesuccess) or a [fail](#log_source-removefail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | log_source        |
| Activity      | remove            |
| Activity Type | log_source-remove |
| Pretty Name   | Log_source Remove |
| Legacy Name   |                   |

log_source-remove:success
-------------------------

There are no fields for this activity type.


log_source-remove:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |