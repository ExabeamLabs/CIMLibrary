log_account-delete
==================

Description
-----------
A log account was Deleted

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | log_account        |
| Activity      | delete             |
| Activity Type | log_account-delete |
| Pretty Name   | Log Account Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log_account-deletesuccess) or a [fail](#log_account-deletefail).


log_account-delete:success
--------------------------

There are no fields for this activity type.


log_account-delete:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |