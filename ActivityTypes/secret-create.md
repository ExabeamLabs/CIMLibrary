secret-create
=============

Description
-----------
Secret credentials were created

The possible fields for this activity type will vary depending on whether the activity was a [success](#secret-createsuccess) or a [fail](#secret-createfail).

| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | secret        |
| Activity      | create        |
| Activity Type | secret-create |
| Pretty Name   | Secret Create |
| Legacy Name   |               |

secret-create:success
---------------------

There are no fields for this activity type.


secret-create:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |