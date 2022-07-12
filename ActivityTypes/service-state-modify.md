service-state-modify
====================

Description
-----------
The execution state of the service was changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#service-state-modifysuccess) or a [fail](#service-state-modifyfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | service              |
| Activity      | state-modify         |
| Activity Type | service-state-modify |
| Pretty Name   | Service State Modify |
| Legacy Name   |                      |

service-state-modify:success
----------------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| service_state |      |           | &#10003;      |

service-state-modify:fail
-------------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| service_state |      |           | &#10003;      |