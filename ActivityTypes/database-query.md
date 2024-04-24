database-query
==============

Description
-----------
A database resource was queried

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | database       |
| Activity      | query          |
| Activity Type | database-query |
| Pretty Name   | Database Query |

Legacy Names
------------
| Success            | Fail               |
| ------------------ | ------------------ |
| database-query<br> | database-query<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-querysuccess) or a [fail](#database-queryfail).


database-query:success
----------------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| db_query      |      | &#10003;  |               |
| response_size |      | &#10003;  |               |

database-query:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| db_query       |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| response_size  |      | &#10003;  |               |