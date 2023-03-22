password-create
===============

Description
-----------
A stored password was created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | password        |
| Activity      | create          |
| Activity Type | password-create |
| Pretty Name   | Password Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-createsuccess) or a [fail](#password-createfail).


password-create:success
-----------------------

There are no fields for this activity type.


password-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |