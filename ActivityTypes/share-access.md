share-access
============

Description
-----------
A network share was accessed

The possible fields for this activity type will vary depending on whether the activity was a [success](#share-accesssuccess) or a [fail](#share-accessfail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | share        |
| Activity      | access       |
| Activity Type | share-access |
| Pretty Name   | Share Access |
| Legacy Name   |              |

share-access:success
--------------------

There are no fields for this activity type.


share-access:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |