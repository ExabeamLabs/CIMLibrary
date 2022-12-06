case-create
===========

Description
-----------
A security incident was created on a security product

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | case        |
| Activity      | create      |
| Activity Type | case-create |
| Pretty Name   | Case Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#case-createsuccess) or a [fail](#case-createfail).


case-create:success
-------------------

There are no fields for this activity type.


case-create:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |