process-memory-allocate
=======================

Description
-----------
Virtual memory was allocated in a process

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-memory-allocatesuccess) or a [fail](#process-memory-allocatefail).

| Parameter     | Value                   |
| ------------- | ----------------------- |
| Subject       | process                 |
| Activity      | memory-allocate         |
| Activity Type | process-memory-allocate |
| Pretty Name   | Process Memory Allocate |
| Legacy Name   |                         |

process-memory-allocate:success
-------------------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| memory_address    |      |           | &#10003;      |
| memory_size       |      |           | &#10003;      |
| memory_protection |      |           | &#10003;      |

process-memory-allocate:fail
----------------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| memory_address    |      |           | &#10003;      |
| memory_size       |      |           | &#10003;      |
| memory_protection |      |           | &#10003;      |