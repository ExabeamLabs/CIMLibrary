database-logout
===============

Description
-----------
A user logged out of a database

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-logoutsuccess) or a [fail](#database-logoutfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | database        |
| Activity      | logout          |
| Activity Type | database-logout |
| Pretty Name   | Database Logout |
| Legacy Name   |                 |

database-logout:success
-----------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

database-logout:fail
--------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |