channel-member-leave
====================

Description
-----------
A member has left or was removed from a communication channel

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | channel              |
| Activity      | member-leave         |
| Activity Type | channel-member-leave |
| Pretty Name   | Channel Member Leave |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#channel-member-leavesuccess) or a [fail](#channel-member-leavefail).


channel-member-leave:success
----------------------------

There are no fields for this activity type.


channel-member-leave:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |