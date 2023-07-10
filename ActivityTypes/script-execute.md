script-execute
==============

Description
-----------
Scripting commands were executed on the system

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | script         |
| Activity      | execute        |
| Activity Type | script-execute |
| Pretty Name   | Script Execute |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#script-executesuccess) or a [fail](#script-executefail).


script-execute:success
----------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| scriptblock_text   |      |           | &#10003;      |
| command_invocation |      | &#10003;  |               |
| local_user_name    |      |           |               |
| user               |      | &#10003;  |               |

script-execute:fail
-------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| scriptblock_text   |      |           | &#10003;      |
| command_invocation |      | &#10003;  |               |
| failure_code       |      | &#10003;  |               |
| local_user_name    |      |           |               |
| failure_reason     |      | &#10003;  |               |
| user               |      | &#10003;  |               |