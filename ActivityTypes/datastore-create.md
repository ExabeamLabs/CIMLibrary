datastore-create
================

Description
-----------
A virtualization datastore was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#datastore-createsuccess) or a [fail](#datastore-createfail).

| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | datastore        |
| Activity      | create           |
| Activity Type | datastore-create |
| Pretty Name   | Datastore Create |
| Legacy Name   |                  |

datastore-create:success
------------------------

There are no fields for this activity type.


datastore-create:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |