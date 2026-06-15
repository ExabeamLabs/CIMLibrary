api_key-modify
==============

Description
-----------
An API key was modified

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | api_key          |
| Activity      | modify           |
| Activity Type | api_key-modify   |
| Pretty Name   | API Key Modified |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#api_key-modifysuccess) or a [fail](#api_key-modifyfail).


api_key-modify:success
----------------------

| Field    | Core | Detection | Informational |
| -------- | ---- | --------- | ------------- |
| key_name |      | &#10003;  |               |
| key_id   |      | &#10003;  |               |

api_key-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| key_id         |      | &#10003;  |               |
| failure_reason |      |           | &#10003;      |