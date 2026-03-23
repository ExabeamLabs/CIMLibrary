ai_agent-delete
===============

Description
-----------
An AI agent was deleted

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | ai_agent         |
| Activity      | delete           |
| Activity Type | ai_agent-delete  |
| Pretty Name   | AI Agent Deleted |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_agent-deletesuccess) or a [fail](#ai_agent-deletefail).


ai_agent-delete:success
-----------------------

There are no fields for this activity type.


ai_agent-delete:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |