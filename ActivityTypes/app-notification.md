app-notification
================

Description
-----------
An app notification is an entirely informational notification that has popped up on an app. This activity only represents informational events that are not "activities".

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | app              |
| Activity      | notification     |
| Activity Type | app-notification |
| Pretty Name   | App Notification |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-notificationsuccess) or a [fail](#app-notificationfail).


app-notification:success
------------------------

| Field | Core | Detection | Informational |
| ----- | ---- | --------- | ------------- |
| cid   |      |           | &#10003;      |

A failure activity is not currently supported for this activity-type.