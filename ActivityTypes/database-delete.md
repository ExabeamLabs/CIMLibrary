database-delete
===============

Description
-----------
A database resource was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-deletesuccess) or a [fail](#database-deletefail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | database        |
| Activity      | delete          |
| Activity Type | database-delete |
| Pretty Name   | Database Delete |
| Legacy Name   |                 |

database-delete:success
-----------------------

There are no fields for this activity type.


database-delete:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |