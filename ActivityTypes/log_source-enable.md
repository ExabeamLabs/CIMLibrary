log_source-enable
=================

Description
-----------


Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | log               |
| Activity      | enable            |
| Activity Type | log_source-enable |
| Pretty Name   | Log Source Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log_source-enablesuccess) or a [fail](#log_source-enablefail).


log_source-enable:success
-------------------------

There are no fields for this activity type.


log_source-enable:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |