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

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| src_ip     |      | &#10003;  |               |
| login_type |      | &#10003;  |               |
| domain     |      | &#10003;  |               |
| dest_ip    |      | &#10003;  |               |
| dest_host  |      | &#10003;  |               |
| src_host   |      | &#10003;  |               |
| user       |      | &#10003;  |               |

database-login:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| src_ip         |      | &#10003;  |               |
| failure_code   |      | &#10003;  |               |
| login_type     |      | &#10003;  |               |
| domain         |      | &#10003;  |               |
| dest_ip        |      | &#10003;  |               |
| dest_host      |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| src_host       |      | &#10003;  |               |
| user           |      | &#10003;  |               |