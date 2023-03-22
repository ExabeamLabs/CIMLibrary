bucket-create
=============

Description
-----------
A bucket was created on the cloud application

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | bucket        |
| Activity      | create        |
| Activity Type | bucket-create |
| Pretty Name   | Bucket Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-createsuccess) or a [fail](#bucket-createfail).


bucket-create:success
---------------------

There are no fields for this activity type.


bucket-create:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |