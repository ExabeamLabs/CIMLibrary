project-modify
==============

Description
-----------
A project was modified

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | project          |
| Activity      | modify           |
| Activity Type | project-modify   |
| Pretty Name   | Project Modified |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#project-modifysuccess) or a [fail](#project-modifyfail).


project-modify:success
----------------------

| Field        | Core | Detection | Informational |
| ------------ | ---- | --------- | ------------- |
| project_id   |      | &#10003;  |               |
| project_name |      | &#10003;  |               |

project-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| project_id     |      | &#10003;  |               |
| failure_reason |      |           | &#10003;      |
| project_name   |      | &#10003;  |               |