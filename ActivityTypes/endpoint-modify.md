endpoint-modify
===============

Description
-----------
An endpoint object or instance properties\configuration were modified

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | endpoint        |
| Activity      | modify          |
| Activity Type | endpoint-modify |
| Pretty Name   | Endpoint Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-modifysuccess) or a [fail](#endpoint-modifyfail).


endpoint-modify:success
-----------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| instance_id   |      |           | &#10003;      |
| modified_keys |      |           | &#10003;      |
| added_keys    |      |           | &#10003;      |

endpoint-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| instance_id    |      |           | &#10003;      |
| modified_keys  |      |           | &#10003;      |
| added_keys     |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |