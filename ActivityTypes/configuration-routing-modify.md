configuration-routing-modify
============================

Description
-----------
The global routing configuration of an application or a program was modified

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-routing-modifysuccess) or a [fail](#configuration-routing-modifyfail).

| Parameter     | Value                        |
| ------------- | ---------------------------- |
| Subject       | configuration                |
| Activity      | routing-modify               |
| Activity Type | configuration-routing-modify |
| Pretty Name   | Configuration Routing Modify |
| Legacy Name   |                              |

configuration-routing-modify:success
------------------------------------

There are no fields for this activity type.


configuration-routing-modify:fail
---------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |