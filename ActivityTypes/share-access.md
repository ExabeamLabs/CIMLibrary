share-access
============

Description
-----------
A network share was accessed

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | share        |
| Activity      | access       |
| Activity Type | share-access |
| Pretty Name   | Share Access |

Legacy Names
------------
| Success          | Fail                    |
| ---------------- | ----------------------- |
| share-access<br> | share-access-denied<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#share-accesssuccess) or a [fail](#share-accessfail).


share-access:success
--------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| src_port  |      | &#10003;  |               |
| file_path |      | &#10003;  |               |

share-access:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| src_port       |      | &#10003;  |               |
| file_path      |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |