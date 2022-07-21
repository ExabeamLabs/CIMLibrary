configuration-create
====================

Description
-----------
A global configuration definition was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-createsuccess) or a [fail](#configuration-createfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | configuration        |
| Activity      | create               |
| Activity Type | configuration-create |
| Pretty Name   | Configuration Create |
| Legacy Name   |                      |

configuration-create:success
----------------------------

There are no fields for this activity type.


configuration-create:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |