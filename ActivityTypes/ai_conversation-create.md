ai_conversation-create
======================

Description
-----------
An AI conversation was created

Parameters
----------
| Parameter     | Value                   |
| ------------- | ----------------------- |
| Subject       | ai_conversation         |
| Activity      | create                  |
| Activity Type | ai_conversation-create  |
| Pretty Name   | AI Conversation Created |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_conversation-createsuccess) or a [fail](#ai_conversation-createfail).


ai_conversation-create:success
------------------------------

There are no fields for this activity type.


ai_conversation-create:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |