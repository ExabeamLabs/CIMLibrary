log_source-modify
=================

Description
-----------
The properties or configuration of a log source contained in a program or an app were changed

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | log_source        |
| Activity      | modify            |
| Activity Type | log_source-modify |
| Pretty Name   | Log_source Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log_source-modifysuccess) or a [fail](#log_source-modifyfail).


log_source-modify:success
-------------------------

There are no fields for this activity type.


log_source-modify:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |