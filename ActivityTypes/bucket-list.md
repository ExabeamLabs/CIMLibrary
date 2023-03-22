bucket-list
===========

Description
-----------
Buckets were enumerated on the application

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | bucket      |
| Activity      | list        |
| Activity Type | bucket-list |
| Pretty Name   | Bucket List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-listsuccess) or a [fail](#bucket-listfail).


bucket-list:success
-------------------

There are no fields for this activity type.


bucket-list:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |