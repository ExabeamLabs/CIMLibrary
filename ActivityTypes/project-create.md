project-create
==============

Description
-----------
A project was created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | project         |
| Activity      | create          |
| Activity Type | project-create  |
| Pretty Name   | Project Created |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#project-createsuccess) or a [fail](#project-createfail).


project-create:success
----------------------

| Field        | Core | Detection | Informational |
| ------------ | ---- | --------- | ------------- |
| project_id   |      | &#10003;  |               |
| project_name |      | &#10003;  |               |

project-create:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| project_id     |      | &#10003;  |               |
| failure_reason |      |           | &#10003;      |
| project_name   |      | &#10003;  |               |