ai_agent-share
==============

Description
-----------
An AI agent was shared

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | ai_agent        |
| Activity      | share           |
| Activity Type | ai_agent-share  |
| Pretty Name   | AI Agent Shared |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_agent-sharesuccess) or a [fail](#ai_agent-sharefail).


ai_agent-share:success
----------------------

There are no fields for this activity type.


ai_agent-share:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |