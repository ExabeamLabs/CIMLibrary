group-member-remove
===================

Description
-----------
A group member was removed from a group

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | group               |
| Activity      | member-remove       |
| Activity Type | group-member-remove |
| Pretty Name   | Group Member Remove |

Legacy Names
------------
| Success            | Fail |
| ------------------ | ---- |
| member-removed<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-member-removesuccess) or a [fail](#group-member-removefail).


group-member-remove:success
---------------------------

| Field     | Core     | Detection | Informational |
| --------- | -------- | --------- | ------------- |
| member    | &#10003; | &#10003;  |               |
| dest_user |          | &#10003;  |               |
| user      |          | &#10003;  |               |

A failure activity is not currently supported for this activity-type.