api_key-delete
==============

Description
-----------
An API key was deleted

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | api_key         |
| Activity      | delete          |
| Activity Type | api_key-delete  |
| Pretty Name   | API Key Deleted |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#api_key-deletesuccess) or a [fail](#api_key-deletefail).


api_key-delete:success
----------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| key_id |      | &#10003;  |               |

api_key-delete:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| key_id         |      | &#10003;  |               |
| failure_reason |      |           | &#10003;      |