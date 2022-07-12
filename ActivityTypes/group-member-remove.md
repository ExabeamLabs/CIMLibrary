group-member-remove
===================

Description
-----------
A group member was removed from a group

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-member-removesuccess) or a [fail](#group-member-removefail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | group               |
| Activity      | member-remove       |
| Activity Type | group-member-remove |
| Pretty Name   | Group Member Remove |
| Legacy Name   |                     |

group-member-remove:success
---------------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| member | &#10003; | &#10003;  |               |

group-member-remove:fail
------------------------

There are no fields for this activity type.
