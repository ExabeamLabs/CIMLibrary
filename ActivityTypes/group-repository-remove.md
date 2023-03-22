group-repository-remove
=======================

Description
-----------
A git repository was removed from a group

Parameters
----------
| Parameter     | Value                   |
| ------------- | ----------------------- |
| Subject       | group                   |
| Activity      | repository-remove       |
| Activity Type | group-repository-remove |
| Pretty Name   | Group Repository Remove |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-repository-removesuccess) or a [fail](#group-repository-removefail).


group-repository-remove:success
-------------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| repository_name |      |           | &#10003;      |

group-repository-remove:fail
----------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| failure_reason  |      | &#10003;  |               |
| repository_name |      |           | &#10003;      |