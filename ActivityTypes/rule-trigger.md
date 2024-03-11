rule-trigger
============

Description
-----------
A trigger of a security rule was recorded on a security product or program

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | rule         |
| Activity      | trigger      |
| Activity Type | rule-trigger |
| Pretty Name   | Rule Trigger |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#rule-triggersuccess) or a [fail](#rule-triggerfail).


rule-trigger:success
--------------------

There are no fields for this activity type.


rule-trigger:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |