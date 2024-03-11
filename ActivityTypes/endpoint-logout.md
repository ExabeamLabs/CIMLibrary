endpoint-logout
===============

Description
-----------
A user logged out of an endpoint

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | endpoint        |
| Activity      | logout          |
| Activity Type | endpoint-logout |
| Pretty Name   | Endpoint Logout |

Legacy Names
------------
| Success                                    | Fail |
| ------------------------------------------ | ---- |
| logout-remote<br>winsession-disconnect<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-logoutsuccess) or a [fail](#endpoint-logoutfail).


endpoint-logout:success
-----------------------

| Field      | Core     | Detection | Informational |
| ---------- | -------- | --------- | ------------- |
| login_type |          | &#10003;  |               |
| domain     |          |           |               |
| logon_type |          | &#10003;  |               |
| user       | &#10003; | &#10003;  |               |

A failure activity is not currently supported for this activity-type.