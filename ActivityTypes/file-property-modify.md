file-property-modify
====================

Description
-----------
The properties of a file were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-property-modifysuccess) or a [fail](#file-property-modifyfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | file                 |
| Activity      | property-modify      |
| Activity Type | file-property-modify |
| Pretty Name   | File Property Modify |
| Legacy Name   |                      |

file-property-modify:success
----------------------------

There are no fields for this activity type.


file-property-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |