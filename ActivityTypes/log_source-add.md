log_source-add
==============

Description
-----------
A log source was added to a program or an app

The possible fields for this activity type will vary depending on whether the activity was a [success](#log_source-addsuccess) or a [fail](#log_source-addfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | log_source     |
| Activity      | add            |
| Activity Type | log_source-add |
| Pretty Name   | Log_source Add |
| Legacy Name   |                |

log_source-add:success
----------------------

There are no fields for this activity type.


log_source-add:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |