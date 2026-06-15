certificate-delete
==================

Description
-----------
A digital certificate object was deleted

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | certificate        |
| Activity      | delete             |
| Activity Type | certificate-delete |
| Pretty Name   | Certificate Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#certificate-deletesuccess) or a [fail](#certificate-deletefail).


certificate-delete:success
--------------------------

There are no fields for this activity type.


certificate-delete:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |