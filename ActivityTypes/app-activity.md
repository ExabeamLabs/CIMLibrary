app-activity
============

Description
-----------
An activity in an application

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | app          |
| Activity      | activity     |
| Activity Type | app-activity |
| Pretty Name   | App Activity |

Legacy Names
------------
| Success                                               | Fail                                                         |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| app-activity<br>webconference-operations-activity<br> | app-activity-failed<br>webconference-operations-activity<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-activitysuccess) or a [fail](#app-activityfail).


app-activity:success
--------------------

| Field                | Core | Detection | Informational |
| -------------------- | ---- | --------- | ------------- |
| os                   |      | &#10003;  |               |
| src_external_country |      | &#10003;  |               |
| mime                 |      | &#10003;  |               |
| local_user_name      |      |           |               |
| src_host             |      | &#10003;  |               |
| src_ip               |      | &#10003;  |               |
| browser              |      | &#10003;  |               |
| fingerprint          |      | &#10003;  |               |
| operation            |      | &#10003;  |               |
| user                 |      | &#10003;  |               |
| user_agent           |      | &#10003;  |               |
| object               |      | &#10003;  |               |
| cid                  |      |           | &#10003;      |

app-activity:fail
-----------------

| Field                | Core | Detection | Informational |
| -------------------- | ---- | --------- | ------------- |
| failure_code         |      | &#10003;  |               |
| os                   |      | &#10003;  |               |
| src_external_country |      | &#10003;  |               |
| mime                 |      | &#10003;  |               |
| local_user_name      |      |           |               |
| failure_reason       |      | &#10003;  |               |
| src_host             |      | &#10003;  |               |
| src_ip               |      | &#10003;  |               |
| src_network_type     |      | &#10003;  |               |
| browser              |      | &#10003;  |               |
| fingerprint          |      | &#10003;  |               |
| operation            |      | &#10003;  |               |
| user                 |      | &#10003;  |               |
| user_agent           |      | &#10003;  |               |
| object               |      | &#10003;  |               |
| cid                  |      |           | &#10003;      |