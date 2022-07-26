email-modify
============

Description
-----------
The properties of an email in an inbox were modified

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | email        |
| Activity      | modify       |
| Activity Type | email-modify |
| Pretty Name   | Email Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#email-modifysuccess) or a [fail](#email-modifyfail).


email-modify:success
--------------------

There are no fields for this activity type.


email-modify:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |