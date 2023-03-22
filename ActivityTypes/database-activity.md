database-activity
=================

Description
-----------
A generic activity took place in a database (catch all)

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | database          |
| Activity      | activity          |
| Activity Type | database-activity |
| Pretty Name   | Database Activity |

Legacy Names
------------
| Success             | Fail                         |
| ------------------- | ---------------------------- |
| database-access<br> | database-activity-failed<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-activitysuccess) or a [fail](#database-activityfail).


database-activity:success
-------------------------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| operation | &#10003; | &#10003;  |               |

database-activity:fail
----------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| operation      | &#10003; | &#10003;  |               |