service-start
=============

Description
-----------
A service was executed

The possible fields for this activity type will vary depending on whether the activity was a [success](#service-startsuccess) or a [fail](#service-startfail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | service       |
| Activity      | start         |
| Activity Type | service-start |
| Pretty Name   | Service Start |
| Legacy Name   |               |

service-start:success
---------------------

There are no fields for this activity type.


service-start:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |