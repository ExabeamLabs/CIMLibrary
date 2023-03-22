parser-disable
==============

Description
-----------
A parser was disabled on a security product or program

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | parser         |
| Activity      | disable        |
| Activity Type | parser-disable |
| Pretty Name   | Parser Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#parser-disablesuccess) or a [fail](#parser-disablefail).


parser-disable:success
----------------------

There are no fields for this activity type.


parser-disable:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |