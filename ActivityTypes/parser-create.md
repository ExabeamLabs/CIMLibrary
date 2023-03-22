parser-create
=============

Description
-----------
A parser was created on a security product or program

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | parser        |
| Activity      | create        |
| Activity Type | parser-create |
| Pretty Name   | Parser Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#parser-createsuccess) or a [fail](#parser-createfail).


parser-create:success
---------------------

There are no fields for this activity type.


parser-create:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |