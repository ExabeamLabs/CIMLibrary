group-delete
============

Description
-----------
A group was deleted

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | group        |
| Activity      | delete       |
| Activity Type | group-delete |
| Pretty Name   | Group Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-deletesuccess) or a [fail](#group-deletefail).


group-delete:success
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| event_locality |      |           | &#10003;      |

group-delete:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |