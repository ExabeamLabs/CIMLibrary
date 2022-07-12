peripheral_storage-activity
===========================

Description
-----------
An activity on a peripheral storage device

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_storage-activitysuccess) or a [fail](#peripheral_storage-activityfail).

| Parameter     | Value                       |
| ------------- | --------------------------- |
| Subject       | peripheral_storage          |
| Activity      | activity                    |
| Activity Type | peripheral_storage-activity |
| Pretty Name   | Peripheral_storage Activity |
| Legacy Name   |                             |

peripheral_storage-activity:success
-----------------------------------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| operation | &#10003; | &#10003;  |               |

peripheral_storage-activity:fail
--------------------------------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| operation | &#10003; | &#10003;  |               |