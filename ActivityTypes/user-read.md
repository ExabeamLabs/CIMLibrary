user-read
=========

Description
-----------
A request to read the properties or configuration of a user was made

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | user      |
| Activity      | read      |
| Activity Type | user-read |
| Pretty Name   | User Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-readsuccess) or a [fail](#user-readfail).


user-read:success
-----------------

There are no fields for this activity type.


user-read:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |