ai_agent-request
================

Description
-----------
A request or prompt was made to an AI agent

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | ai_agent         |
| Activity      | request          |
| Activity Type | ai_agent-request |
| Pretty Name   | AI Agent Request |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_agent-requestsuccess) or a [fail](#ai_agent-requestfail).


ai_agent-request:success
------------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| categories    |      |           | &#10003;      |
| result_reason |      |           | &#10003;      |

ai_agent-request:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |
| categories     |      |           | &#10003;      |
| result_reason  |      |           | &#10003;      |