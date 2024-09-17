collector-disable
=================

Description
-----------
Collector was disabled

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | collector         |
| Activity      | disable           |
| Activity Type | collector-disable |
| Pretty Name   | Collector disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#collector-disablesuccess) or a [fail](#collector-disablefail).


collector-disable:success
-------------------------

There are no fields for this activity type.


collector-disable:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |