ds-replication-stop
===================

Description
-----------
A directory service replication has ended

The possible fields for this activity type will vary depending on whether the activity was a [success](#ds-replication-stopsuccess) or a [fail](#ds-replication-stopfail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | ds                  |
| Activity      | replication-stop    |
| Activity Type | ds-replication-stop |
| Pretty Name   | Ds Replication Stop |
| Legacy Name   |                     |

ds-replication-stop:success
---------------------------

There are no fields for this activity type.


ds-replication-stop:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |