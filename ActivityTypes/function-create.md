function-create
===============

Description
-----------
An automation cloud function was created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | function        |
| Activity      | create          |
| Activity Type | function-create |
| Pretty Name   | Function Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#function-createsuccess) or a [fail](#function-createfail).


function-create:success
-----------------------

There are no fields for this activity type.


function-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |