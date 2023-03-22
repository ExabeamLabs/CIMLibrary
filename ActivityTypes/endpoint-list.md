endpoint-list
=============

Description
-----------
Multiple endpoint objects have been enumerated

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | endpoint      |
| Activity      | list          |
| Activity Type | endpoint-list |
| Pretty Name   | Endpoint List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-listsuccess) or a [fail](#endpoint-listfail).


endpoint-list:success
---------------------

There are no fields for this activity type.


endpoint-list:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |