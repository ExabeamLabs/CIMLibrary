database-login
==============

Description
-----------
A user logged in to a database

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | database       |
| Activity      | login          |
| Activity Type | database-login |
| Pretty Name   | Database Login |

Legacy Names
------------
| Success            | Fail                      |
| ------------------ | ------------------------- |
| database-login<br> | database-failed-login<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-loginsuccess) or a [fail](#database-loginfail).


database-login:success
----------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

database-login:fail
-------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| domain         |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| user           | &#10003; | &#10003;  |               |