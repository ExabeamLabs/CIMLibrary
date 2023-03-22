parser-enable
=============

Description
-----------
A parser was enabled on a security product or program

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | parser        |
| Activity      | enable        |
| Activity Type | parser-enable |
| Pretty Name   | Parser Enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#parser-enablesuccess) or a [fail](#parser-enablefail).


parser-enable:success
---------------------

There are no fields for this activity type.


parser-enable:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |