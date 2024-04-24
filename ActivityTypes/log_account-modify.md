log_account-modify
==================

Description
-----------
A log account was Modified

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | log_account        |
| Activity      | modify             |
| Activity Type | log_account-modify |
| Pretty Name   | Log Account Modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log_account-modifysuccess) or a [fail](#log_account-modifyfail).


log_account-modify:success
--------------------------

There are no fields for this activity type.


log_account-modify:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |