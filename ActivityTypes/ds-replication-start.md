ds-replication-start
====================

Description
-----------
A directory service replication has started

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | ds                   |
| Activity      | replication-start    |
| Activity Type | ds-replication-start |
| Pretty Name   | Ds Replication Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds-replication-startsuccess) or a [fail](#ds-replication-startfail).


ds-replication-start:success
----------------------------

There are no fields for this activity type.


ds-replication-start:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |