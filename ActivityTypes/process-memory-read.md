process-memory-read
===================

Description
-----------
Virtual memory was read from a process

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | process             |
| Activity      | memory-read         |
| Activity Type | process-memory-read |
| Pretty Name   | Process Memory Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-memory-readsuccess) or a [fail](#process-memory-readfail).


process-memory-read:success
---------------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| memory_address    |      |           | &#10003;      |
| memory_size       |      |           | &#10003;      |
| memory_protection |      |           | &#10003;      |

process-memory-read:fail
------------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| failure_code      |      | &#10003;  |               |
| memory_address    |      |           | &#10003;      |
| failure_reason    |      | &#10003;  |               |
| memory_size       |      |           | &#10003;      |
| memory_protection |      |           | &#10003;      |