ai_agent-publish
================

Description
-----------
An AI agent was published

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | ai_agent           |
| Activity      | publish            |
| Activity Type | ai_agent-publish   |
| Pretty Name   | AI Agent Published |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_agent-publishsuccess) or a [fail](#ai_agent-publishfail).


ai_agent-publish:success
------------------------

There are no fields for this activity type.


ai_agent-publish:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |