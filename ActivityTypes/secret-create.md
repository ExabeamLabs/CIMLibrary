secret-create
=============

Description
-----------
Secret credentials were created

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | secret        |
| Activity      | create        |
| Activity Type | secret-create |
| Pretty Name   | Secret Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#secret-createsuccess) or a [fail](#secret-createfail).


secret-create:success
---------------------

There are no fields for this activity type.


secret-create:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |