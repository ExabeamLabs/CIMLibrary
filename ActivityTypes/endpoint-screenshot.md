endpoint-screenshot
===================

Description
-----------
A screenshot of an endpoint was taken

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-screenshotsuccess) or a [fail](#endpoint-screenshotfail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | endpoint            |
| Activity      | screenshot          |
| Activity Type | endpoint-screenshot |
| Pretty Name   | Endpoint Screenshot |
| Legacy Name   |                     |

endpoint-screenshot:success
---------------------------

There are no fields for this activity type.


endpoint-screenshot:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |