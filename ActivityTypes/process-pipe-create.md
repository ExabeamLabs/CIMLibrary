process-pipe-create
===================

Description
-----------
An inter-process communication pipe was created in a process

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-pipe-createsuccess) or a [fail](#process-pipe-createfail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | process             |
| Activity      | pipe-create         |
| Activity Type | process-pipe-create |
| Pretty Name   | Process Pipe Create |
| Legacy Name   |                     |

process-pipe-create:success
---------------------------

There are no fields for this activity type.


process-pipe-create:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |