meeting-member-leave
====================

Description
-----------
A user left a web meeting

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | meeting              |
| Activity      | member-leave         |
| Activity Type | meeting-member-leave |
| Pretty Name   | Meeting Member Leave |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#meeting-member-leavesuccess) or a [fail](#meeting-member-leavefail).


meeting-member-leave:success
----------------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| member | &#10003; | &#10003;  |               |

A failure activity is not currently supported for this activity-type.