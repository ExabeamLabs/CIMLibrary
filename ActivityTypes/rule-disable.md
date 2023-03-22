rule-disable
============

Description
-----------
A security rule was disabled on a security product or program

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | rule         |
| Activity      | disable      |
| Activity Type | rule-disable |
| Pretty Name   | Rule Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#rule-disablesuccess) or a [fail](#rule-disablefail).


rule-disable:success
--------------------

There are no fields for this activity type.


rule-disable:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |