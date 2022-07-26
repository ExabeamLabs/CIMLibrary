channel-member-join
===================

Description
-----------
A member has joined or was added into a communication channel

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | channel             |
| Activity      | member-join         |
| Activity Type | channel-member-join |
| Pretty Name   | Channel Member Join |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#channel-member-joinsuccess) or a [fail](#channel-member-joinfail).


channel-member-join:success
---------------------------

There are no fields for this activity type.


channel-member-join:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |