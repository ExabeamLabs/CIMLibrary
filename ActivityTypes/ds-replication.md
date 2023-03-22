ds-replication
==============

Description
-----------
A part of a directory service replication process is taking place

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | ds             |
| Activity      | replication    |
| Activity Type | ds-replication |
| Pretty Name   | Ds Replication |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds-replicationsuccess) or a [fail](#ds-replicationfail).


ds-replication:success
----------------------

There are no fields for this activity type.


ds-replication:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |