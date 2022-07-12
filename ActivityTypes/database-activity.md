database-activity
=================

Description
-----------
A generic activity took place in a database (catch all)

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-activitysuccess) or a [fail](#database-activityfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | database          |
| Activity      | activity          |
| Activity Type | database-activity |
| Pretty Name   | Database Activity |
| Legacy Name   |                   |

database-activity:success
-------------------------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| operation | &#10003; | &#10003;  |               |

database-activity:fail
----------------------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| operation | &#10003; | &#10003;  |               |