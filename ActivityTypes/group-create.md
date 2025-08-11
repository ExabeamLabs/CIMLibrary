group-create
============

Description
-----------
A group was created

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | group        |
| Activity      | create       |
| Activity Type | group-create |
| Pretty Name   | Group Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-createsuccess) or a [fail](#group-createfail).


group-create:success
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| event_locality |      |           | &#10003;      |

group-create:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |