rule-modify
===========

Description
-----------


Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | rule        |
| Activity      | modify      |
| Activity Type | rule-modify |
| Pretty Name   | Rule Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#rule-modifysuccess) or a [fail](#rule-modifyfail).


rule-modify:success
-------------------

There are no fields for this activity type.


rule-modify:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |