endpoint-logout
===============

Description
-----------
A user logged out of an endpoint

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-logoutsuccess) or a [fail](#endpoint-logoutfail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | endpoint        |
| Activity      | logout          |
| Activity Type | endpoint-logout |
| Pretty Name   | Endpoint Logout |
| Legacy Name   |                 |

endpoint-logout:success
-----------------------

| Field      | Core     | Detection | Informational |
| ---------- | -------- | --------- | ------------- |
| login_type |          | &#10003;  |               |
| domain     |          |           |               |
| user       | &#10003; | &#10003;  |               |

endpoint-logout:fail
--------------------

There are no fields for this activity type.
