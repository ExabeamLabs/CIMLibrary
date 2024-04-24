process-memory-protect
======================

Description
-----------
Virtual memory was protected

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | process                |
| Activity      | memory-protect         |
| Activity Type | process-memory-protect |
| Pretty Name   | Process Memory Protect |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-memory-protectsuccess) or a [fail](#process-memory-protectfail).


process-memory-protect:success
------------------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| memory_address    |      |           | &#10003;      |
| memory_size       |      |           | &#10003;      |
| memory_protection |      |           | &#10003;      |

process-memory-protect:fail
---------------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| failure_code      |      | &#10003;  |               |
| memory_address    |      |           | &#10003;      |
| failure_reason    |      | &#10003;  |               |
| memory_size       |      |           | &#10003;      |
| memory_protection |      |           | &#10003;      |