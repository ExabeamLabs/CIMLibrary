peripheral_storage-activity
===========================

Description
-----------
An activity on a peripheral storage device

Parameters
----------
| Parameter     | Value                       |
| ------------- | --------------------------- |
| Subject       | peripheral_storage          |
| Activity      | activity                    |
| Activity Type | peripheral_storage-activity |
| Pretty Name   | Peripheral_storage Activity |

Legacy Names
------------
| Success          | Fail                    |
| ---------------- | ----------------------- |
| usb-activity<br> | failed-usb-activity<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_storage-activitysuccess) or a [fail](#peripheral_storage-activityfail).


peripheral_storage-activity:success
-----------------------------------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| operation | &#10003; | &#10003;  |               |

peripheral_storage-activity:fail
--------------------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| operation      | &#10003; | &#10003;  |               |