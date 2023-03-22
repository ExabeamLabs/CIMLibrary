function-write
==============

Description
-----------
An automation cloud function was created or modified, only used as a catch all if create or modify cannot be determined

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | function       |
| Activity      | write          |
| Activity Type | function-write |
| Pretty Name   | Function Write |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#function-writesuccess) or a [fail](#function-writefail).


function-write:success
----------------------

There are no fields for this activity type.


function-write:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |