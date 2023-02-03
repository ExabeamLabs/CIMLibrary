log-search_export
==========

Description
-----------
An export was performed on an audit log or audit logs entries

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | log               |
| Activity      | export            |
| Activity Type | log-search_export |
| Pretty Name   | Log Search Export |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-search_exportsuccess) or a [fail](#log-search_exportfail).


log-search_export:success
------------------

There are no fields for this activity type.


log-search_export:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
