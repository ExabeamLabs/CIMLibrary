file-search
===========

Description
-----------
A search was performed on files

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | file        |
| Activity      | search      |
| Activity Type | file-search |
| Pretty Name   | File Search |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-searchsuccess) or a [fail](#file-searchfail).


file-search:success
-------------------

There are no fields for this activity type.


file-search:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |