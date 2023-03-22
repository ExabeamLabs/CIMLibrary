smtp-start
==========

Description
-----------
A SMTP sesssion was initiated

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | smtp       |
| Activity      | start      |
| Activity Type | smtp-start |
| Pretty Name   | Smtp Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#smtp-startsuccess) or a [fail](#smtp-startfail).


smtp-start:success
------------------

There are no fields for this activity type.


smtp-start:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |