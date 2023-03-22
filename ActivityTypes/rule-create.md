rule-create
===========

Description
-----------
A security rule was created on a security product or program

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | rule        |
| Activity      | create      |
| Activity Type | rule-create |
| Pretty Name   | Rule Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#rule-createsuccess) or a [fail](#rule-createfail).


rule-create:success
-------------------

There are no fields for this activity type.


rule-create:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |