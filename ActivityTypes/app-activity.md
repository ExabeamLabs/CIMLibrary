app-activity
============

Description
-----------
An activity in an application

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-activitysuccess) or a [fail](#app-activityfail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | app          |
| Activity      | activity     |
| Activity Type | app-activity |
| Pretty Name   | App Activity |
| Legacy Name   |              |

app-activity:success
--------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| operation |      |           |               |

app-activity:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| operation      |      |           |               |