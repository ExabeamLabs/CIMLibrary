log_source-disable
==================

Description
-----------


Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | log                |
| Activity      | disable            |
| Activity Type | log_source-disable |
| Pretty Name   | Log Source Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log_source-disablesuccess) or a [fail](#log_source-disablefail).


log_source-disable:success
--------------------------

There are no fields for this activity type.


log_source-disable:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |