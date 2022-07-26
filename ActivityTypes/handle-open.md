handle-open
===========

Description
-----------
A windows handle was opened, giving access to the linked object

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | handle      |
| Activity      | open        |
| Activity Type | handle-open |
| Pretty Name   | Handle Open |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#handle-opensuccess) or a [fail](#handle-openfail).


handle-open:success
-------------------

There are no fields for this activity type.


handle-open:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |