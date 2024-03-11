password-copy
=============

Description
-----------
A stored password object was copied, and a new object was created

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | password      |
| Activity      | copy          |
| Activity Type | password-copy |
| Pretty Name   | Password Copy |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#password-copysuccess) or a [fail](#password-copyfail).


password-copy:success
---------------------

| Field        | Core | Detection | Informational |
| ------------ | ---- | --------- | ------------- |
| src_password |      |           | &#10003;      |

password-copy:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| src_password   |      |           | &#10003;      |