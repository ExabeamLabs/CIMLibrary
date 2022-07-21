file-search
===========

Description
-----------
A search was performed on files

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-searchsuccess) or a [fail](#file-searchfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | file        |
| Activity      | search      |
| Activity Type | file-search |
| Pretty Name   | File Search |
| Legacy Name   |             |

file-search:success
-------------------

There are no fields for this activity type.


file-search:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |