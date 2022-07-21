registry-create
===============

Description
-----------
A registry object was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#registry-createsuccess) or a [fail](#registry-createfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | registry        |
| Activity      | create          |
| Activity Type | registry-create |
| Pretty Name   | Registry Create |
| Legacy Name   |                 |

registry-create:success
-----------------------

There are no fields for this activity type.


registry-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |