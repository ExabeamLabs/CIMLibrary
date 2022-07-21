key-create
==========

Description
-----------
A global key object was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#key-createsuccess) or a [fail](#key-createfail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | key        |
| Activity      | create     |
| Activity Type | key-create |
| Pretty Name   | Key Create |
| Legacy Name   |            |

key-create:success
------------------

There are no fields for this activity type.


key-create:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |