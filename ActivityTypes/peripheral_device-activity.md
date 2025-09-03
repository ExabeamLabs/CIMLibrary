peripheral_device-activity
==========================

Description
-----------
An activity on a peripheral device

Parameters
----------
| Parameter     | Value                      |
| ------------- | -------------------------- |
| Subject       | peripheral_device          |
| Activity      | activity                   |
| Activity Type | peripheral_device-activity |
| Pretty Name   | Peripheral_device Activity |

Legacy Names
------------
| Success          | Fail                    |
| ---------------- | ----------------------- |
| usb-activity<br> | failed-usb-activity<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#peripheral_device-activitysuccess) or a [fail](#peripheral_device-activityfail).


peripheral_device-activity:success
----------------------------------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| operation | &#10003; | &#10003;  |               |
| cid       |          |           | &#10003;      |

peripheral_device-activity:fail
-------------------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| operation      | &#10003; | &#10003;  |               |
| cid            |          |           | &#10003;      |