user-device-remember
====================

Description
-----------
A user has requested that his device configuration will be remembered on future usage in this system

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | user                 |
| Activity      | device-remember      |
| Activity Type | user-device-remember |
| Pretty Name   | User Device Remember |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#user-device-remembersuccess) or a [fail](#user-device-rememberfail).


user-device-remember:success
----------------------------

There are no fields for this activity type.


user-device-remember:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |