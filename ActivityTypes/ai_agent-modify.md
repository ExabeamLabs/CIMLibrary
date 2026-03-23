ai_agent-modify
===============

Description
-----------
An AI agent was modified

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | ai_agent          |
| Activity      | modify            |
| Activity Type | ai_agent-modify   |
| Pretty Name   | AI Agent Modified |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_agent-modifysuccess) or a [fail](#ai_agent-modifyfail).


ai_agent-modify:success
-----------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| operation |      | &#10003;  |               |

ai_agent-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |
| operation      |      | &#10003;  |               |