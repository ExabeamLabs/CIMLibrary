log-search
==========

Description
-----------
A search was performed on an audit log or audit logs entries

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-searchsuccess) or a [fail](#log-searchfail).

| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | log        |
| Activity      | search     |
| Activity Type | log-search |
| Pretty Name   | Log Search |
| Legacy Name   |            |

log-search:success
------------------

There are no fields for this activity type.


log-search:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |