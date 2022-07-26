ds-replication-stop
===================

Description
-----------
A directory service replication has ended

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | ds                  |
| Activity      | replication-stop    |
| Activity Type | ds-replication-stop |
| Pretty Name   | Ds Replication Stop |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds-replication-stopsuccess) or a [fail](#ds-replication-stopfail).


ds-replication-stop:success
---------------------------

There are no fields for this activity type.


ds-replication-stop:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |