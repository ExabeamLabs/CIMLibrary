policy-list
===========

Description
-----------
An enumeration of security policies took place

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | policy      |
| Activity      | list        |
| Activity Type | policy-list |
| Pretty Name   | Policy List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#policy-listsuccess) or a [fail](#policy-listfail).


policy-list:success
-------------------

There are no fields for this activity type.


policy-list:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |