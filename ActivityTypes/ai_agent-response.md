ai_agent-response
=================

Description
-----------
An AI agent successfully responded to a request or prompt

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | ai_agent          |
| Activity      | response          |
| Activity Type | ai_agent-response |
| Pretty Name   | AI Agent Response |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_agent-responsesuccess) or a [fail](#ai_agent-responsefail).


ai_agent-response:success
-------------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| result             |      |           | &#10003;      |
| workspace_id       |      | &#10003;  |               |
| ai_tool_name       |      | &#10003;  |               |
| ai_token_in_count  |      | &#10003;  |               |
| ai_token_out_count |      | &#10003;  |               |
| categories         |      |           | &#10003;      |
| ai_token_count     |      | &#10003;  |               |
| llm_response       |      | &#10003;  |               |
| ai_function_name   |      | &#10003;  |               |
| result_reason      |      |           | &#10003;      |

ai_agent-response:fail
----------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| result             |      |           | &#10003;      |
| workspace_id       |      | &#10003;  |               |
| failure_code       |      |           | &#10003;      |
| ai_tool_name       |      | &#10003;  |               |
| ai_token_in_count  |      | &#10003;  |               |
| ai_token_out_count |      | &#10003;  |               |
| failure_reason     |      |           | &#10003;      |
| categories         |      |           | &#10003;      |
| ai_token_count     |      | &#10003;  |               |
| llm_response       |      | &#10003;  |               |
| ai_function_name   |      | &#10003;  |               |
| result_reason      |      |           | &#10003;      |