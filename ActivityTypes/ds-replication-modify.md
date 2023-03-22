ds-replication-modify
=====================

Description
-----------
The configuration of the replication process of the directory service was modified

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | ds                    |
| Activity      | replication-modify    |
| Activity Type | ds-replication-modify |
| Pretty Name   | Ds Replication Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds-replication-modifysuccess) or a [fail](#ds-replication-modifyfail).


ds-replication-modify:success
-----------------------------

There are no fields for this activity type.


ds-replication-modify:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |