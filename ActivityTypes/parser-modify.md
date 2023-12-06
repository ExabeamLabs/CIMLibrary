parser-modify
=============

Description
-----------
A parser was modified on a security product or program

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | parser        |
| Activity      | modify        |
| Activity Type | parser-modify |
| Pretty Name   | Parser Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#parser-modifysuccess) or a [fail](#parser-modifyfail).


parser-modify:success
---------------------

There are no fields for this activity type.


parser-modify:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |