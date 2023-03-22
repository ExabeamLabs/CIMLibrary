parser-import
=============

Description
-----------
A parser was imported on a security product or program

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | parser        |
| Activity      | import        |
| Activity Type | parser-import |
| Pretty Name   | Parser Import |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#parser-importsuccess) or a [fail](#parser-importfail).


parser-import:success
---------------------

There are no fields for this activity type.


parser-import:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |