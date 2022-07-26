ds_object-read
==============

Description
-----------
A request was made to read the information of a directory service object 

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | ds_object      |
| Activity      | read           |
| Activity Type | ds_object-read |
| Pretty Name   | Ds_object Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds_object-readsuccess) or a [fail](#ds_object-readfail).


ds_object-read:success
----------------------

There are no fields for this activity type.


ds_object-read:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |