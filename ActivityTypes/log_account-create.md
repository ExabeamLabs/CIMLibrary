log_account-create
==================

Description
-----------
A log account was created

Parameters
----------
| Parameter     | Value              |
| ------------- | ------------------ |
| Subject       | log_account        |
| Activity      | create             |
| Activity Type | log_account-create |
| Pretty Name   | Log Account Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log_account-createsuccess) or a [fail](#log_account-createfail).


log_account-create:success
--------------------------

There are no fields for this activity type.


log_account-create:fail
-----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |