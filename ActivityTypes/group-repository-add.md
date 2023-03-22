group-repository-add
====================

Description
-----------
A git repository was associated with the group

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | group                |
| Activity      | repository-add       |
| Activity Type | group-repository-add |
| Pretty Name   | Group Repository Add |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-repository-addsuccess) or a [fail](#group-repository-addfail).


group-repository-add:success
----------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| repository_name |      |           | &#10003;      |

group-repository-add:fail
-------------------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| failure_reason  |      | &#10003;  |               |
| repository_name |      |           | &#10003;      |