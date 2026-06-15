app-modify
==========

Description
-----------
An application was updated

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | app          |
| Activity      | modify       |
| Activity Type | app-modify   |
| Pretty Name   | App Modified |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-modifysuccess) or a [fail](#app-modifyfail).


app-modify:success
------------------

There are no fields for this activity type.


app-modify:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |