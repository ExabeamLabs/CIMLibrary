service-modify
==============

Description
-----------
The properties or configuration of the service object were updated

The possible fields for this activity type will vary depending on whether the activity was a [success](#service-modifysuccess) or a [fail](#service-modifyfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | service        |
| Activity      | modify         |
| Activity Type | service-modify |
| Pretty Name   | Service Modify |
| Legacy Name   |                |

service-modify:success
----------------------

There are no fields for this activity type.


service-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |