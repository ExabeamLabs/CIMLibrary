physical_location-access
========================

Description
-----------
A user opened a door, gate, or any other entrance using their badge

The possible fields for this activity type will vary depending on whether the activity was a [success](#physical_location-accesssuccess) or a [fail](#physical_location-accessfail).

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | physical_location        |
| Activity      | access                   |
| Activity Type | physical_location-access |
| Pretty Name   | Physical_location Access |
| Legacy Name   |                          |

physical_location-access:success
--------------------------------

| Field | Core     | Detection | Informational |
| ----- | -------- | --------- | ------------- |
| user  | &#10003; | &#10003;  |               |

physical_location-access:fail
-----------------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| user           | &#10003; | &#10003;  |               |