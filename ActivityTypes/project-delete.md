project-delete
==============

Description
-----------
A project was deleted

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | project         |
| Activity      | delete          |
| Activity Type | project-delete  |
| Pretty Name   | Project Deleted |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#project-deletesuccess) or a [fail](#project-deletefail).


project-delete:success
----------------------

| Field        | Core | Detection | Informational |
| ------------ | ---- | --------- | ------------- |
| project_id   |      | &#10003;  |               |
| project_name |      | &#10003;  |               |

project-delete:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| project_id     |      | &#10003;  |               |
| failure_reason |      |           | &#10003;      |
| project_name   |      | &#10003;  |               |