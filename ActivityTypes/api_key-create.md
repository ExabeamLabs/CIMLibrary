api_key-create
==============

Description
-----------
An API key was created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | api_key         |
| Activity      | create          |
| Activity Type | api_key-create  |
| Pretty Name   | API Key Created |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#api_key-createsuccess) or a [fail](#api_key-createfail).


api_key-create:success
----------------------

| Field  | Core | Detection | Informational |
| ------ | ---- | --------- | ------------- |
| key_id |      | &#10003;  |               |

api_key-create:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| key_id         |      | &#10003;  |               |
| failure_reason |      |           | &#10003;      |