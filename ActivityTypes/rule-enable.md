rule-enable
===========

Description
-----------
A security rule was enabled on a security product or program

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | rule        |
| Activity      | enable      |
| Activity Type | rule-enable |
| Pretty Name   | Rule Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#rule-enablesuccess) or a [fail](#rule-enablefail).


rule-enable:success
-------------------

There are no fields for this activity type.


rule-enable:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |