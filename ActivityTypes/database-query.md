database-query
==============

Description
-----------
A database resource was queried

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-querysuccess) or a [fail](#database-queryfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | database       |
| Activity      | query          |
| Activity Type | database-query |
| Pretty Name   | Database Query |
| Legacy Name   |                |

database-query:success
----------------------

| Field    | Core | Detection | Informational |
| -------- | ---- | --------- | ------------- |
| db_query |      | &#10003;  |               |

database-query:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| db_query       |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |