snapshot-modify
===============

Description
-----------
The configuration or properties of a snapshot were modified

The possible fields for this activity type will vary depending on whether the activity was a [success](#snapshot-modifysuccess) or a [fail](#snapshot-modifyfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | snapshot        |
| Activity      | modify          |
| Activity Type | snapshot-modify |
| Pretty Name   | Snapshot Modify |
| Legacy Name   |                 |

snapshot-modify:success
-----------------------

There are no fields for this activity type.


snapshot-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |