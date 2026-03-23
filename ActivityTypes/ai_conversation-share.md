ai_conversation-share
=====================

Description
-----------
An AI conversation was shared

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | ai_conversation        |
| Activity      | share                  |
| Activity Type | ai_conversation-share  |
| Pretty Name   | AI Conversation Shared |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_conversation-sharesuccess) or a [fail](#ai_conversation-sharefail).


ai_conversation-share:success
-----------------------------

There are no fields for this activity type.


ai_conversation-share:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |