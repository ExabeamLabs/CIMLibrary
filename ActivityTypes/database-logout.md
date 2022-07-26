database-logout
===============

Description
-----------
A user logged out of a database

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | database        |
| Activity      | logout          |
| Activity Type | database-logout |
| Pretty Name   | Database Logout |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-logoutsuccess) or a [fail](#database-logoutfail).


database-logout:success
-----------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

database-logout:fail
--------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| failure_code   |          | &#10003;  |               |
| domain         |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |
| user           | &#10003; | &#10003;  |               |