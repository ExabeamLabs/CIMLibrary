template-create
===============

Description
-----------
Template Created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | template        |
| Activity      | create          |
| Activity Type | template-create |
| Pretty Name   | Template Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#template-createsuccess) or a [fail](#template-createfail).


template-create:success
-----------------------

There are no fields for this activity type.


template-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |