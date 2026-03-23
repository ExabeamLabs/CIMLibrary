ai_agent-create
===============

Description
-----------
An AI agent was created

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | ai_agent         |
| Activity      | create           |
| Activity Type | ai_agent-create  |
| Pretty Name   | AI Agent Created |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_agent-createsuccess) or a [fail](#ai_agent-createfail).


ai_agent-create:success
-----------------------

There are no fields for this activity type.


ai_agent-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |