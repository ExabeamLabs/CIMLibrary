log-export
==========

Description
-----------
An audit log was exported from a remote site

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | log        |
| Activity      | export     |
| Activity Type | log-export |
| Pretty Name   | Log Export |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-exportsuccess) or a [fail](#log-exportfail).


log-export:success
------------------

There are no fields for this activity type.


log-export:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |