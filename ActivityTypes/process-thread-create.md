process-thread-create
=====================

Description
-----------
A thread was created in a process

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-thread-createsuccess) or a [fail](#process-thread-createfail).

| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | process               |
| Activity      | thread-create         |
| Activity Type | process-thread-create |
| Pretty Name   | Process Thread Create |
| Legacy Name   |                       |

process-thread-create:success
-----------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| thread_id |      |           |               |

process-thread-create:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| thread_id      |      |           |               |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |