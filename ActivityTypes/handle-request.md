handle-request
==============

Description
-----------
A request was made to get access to a windows handle

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | handle         |
| Activity      | request        |
| Activity Type | handle-request |
| Pretty Name   | Handle Request |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#handle-requestsuccess) or a [fail](#handle-requestfail).


handle-request:success
----------------------

There are no fields for this activity type.


handle-request:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |