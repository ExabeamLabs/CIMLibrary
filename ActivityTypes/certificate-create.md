certificate-create
==================

Description
-----------
A digital certificate object was created

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | certificate        |
| Activity      | create             |
| Activity Type | certificate-create |
| Pretty Name   | Certificate Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#certificate-createsuccess) or a [fail](#certificate-createfail).


certificate-create:success
--------------------------

There are no fields for this activity type.


certificate-create:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |