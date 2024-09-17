collector-enable
================

Description
-----------
Collector was enabled

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | collector        |
| Activity      | enable           |
| Activity Type | collector-enable |
| Pretty Name   | Collector enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#collector-enablesuccess) or a [fail](#collector-enablefail).


collector-enable:success
------------------------

There are no fields for this activity type.


collector-enable:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |