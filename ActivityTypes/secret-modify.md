secret-modify
=============

Description
-----------
The vaule of secret credentails was changed

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | secret        |
| Activity      | modify        |
| Activity Type | secret-modify |
| Pretty Name   | Secret Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#secret-modifysuccess) or a [fail](#secret-modifyfail).


secret-modify:success
---------------------

There are no fields for this activity type.


secret-modify:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |