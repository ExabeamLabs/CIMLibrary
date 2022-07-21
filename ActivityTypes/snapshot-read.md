snapshot-read
=============

Description
-----------
A request to read the content of a snapshot was made

The possible fields for this activity type will vary depending on whether the activity was a [success](#snapshot-readsuccess) or a [fail](#snapshot-readfail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | snapshot      |
| Activity      | read          |
| Activity Type | snapshot-read |
| Pretty Name   | Snapshot Read |
| Legacy Name   |               |

snapshot-read:success
---------------------

There are no fields for this activity type.


snapshot-read:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |