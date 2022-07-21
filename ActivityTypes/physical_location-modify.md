physical_location-modify
========================

Description
-----------
The properties of the digital representation of the door, gate, or any other physical location were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#physical_location-modifysuccess) or a [fail](#physical_location-modifyfail).

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | physical_location        |
| Activity      | modify                   |
| Activity Type | physical_location-modify |
| Pretty Name   | Physical_location Modify |
| Legacy Name   |                          |

physical_location-modify:success
--------------------------------

There are no fields for this activity type.


physical_location-modify:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |