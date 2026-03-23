ai_conversation-delete
======================

Description
-----------
An AI conversation was deleted

Parameters
----------
| Parameter     | Value                   |
| ------------- | ----------------------- |
| Subject       | ai_conversation         |
| Activity      | delete                  |
| Activity Type | ai_conversation-delete  |
| Pretty Name   | AI Conversation Deleted |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ai_conversation-deletesuccess) or a [fail](#ai_conversation-deletefail).


ai_conversation-delete:success
------------------------------

There are no fields for this activity type.


ai_conversation-delete:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      |           | &#10003;      |
| failure_reason |      |           | &#10003;      |