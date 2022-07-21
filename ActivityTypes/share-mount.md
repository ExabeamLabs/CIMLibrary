share-mount
===========

Description
-----------
A network share was mounted as a volume on an endpoint or an app

The possible fields for this activity type will vary depending on whether the activity was a [success](#share-mountsuccess) or a [fail](#share-mountfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | share       |
| Activity      | mount       |
| Activity Type | share-mount |
| Pretty Name   | Share Mount |
| Legacy Name   |             |

share-mount:success
-------------------

There are no fields for this activity type.


share-mount:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |