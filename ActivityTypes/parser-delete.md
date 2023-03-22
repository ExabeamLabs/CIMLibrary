parser-delete
=============

Description
-----------
A parser was deleted on a security product or program

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | parser        |
| Activity      | delete        |
| Activity Type | parser-delete |
| Pretty Name   | Parser Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#parser-deletesuccess) or a [fail](#parser-deletefail).


parser-delete:success
---------------------

There are no fields for this activity type.


parser-delete:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |