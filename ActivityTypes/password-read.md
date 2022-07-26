password-read
=============

Description
-----------
The value of a stored password was read

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | password      |
| Activity      | read          |
| Activity Type | password-read |
| Pretty Name   | Password Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-readsuccess) or a [fail](#password-readfail).


password-read:success
---------------------

There are no fields for this activity type.


password-read:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |