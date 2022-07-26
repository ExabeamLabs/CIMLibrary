port-disable
============

Description
-----------
A port was disabled

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | port         |
| Activity      | disable      |
| Activity Type | port-disable |
| Pretty Name   | Port Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#port-disablesuccess) or a [fail](#port-disablefail).


port-disable:success
--------------------

There are no fields for this activity type.


port-disable:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |