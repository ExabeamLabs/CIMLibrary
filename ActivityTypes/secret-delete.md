secret-delete
=============

Description
-----------
Secret credentials were deleted

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | secret        |
| Activity      | delete        |
| Activity Type | secret-delete |
| Pretty Name   | Secret Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#secret-deletesuccess) or a [fail](#secret-deletefail).


secret-delete:success
---------------------

There are no fields for this activity type.


secret-delete:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |