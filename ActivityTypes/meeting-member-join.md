meeting-member-join
===================

Description
-----------
A user joined a web meeting

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | meeting             |
| Activity      | member-join         |
| Activity Type | meeting-member-join |
| Pretty Name   | Meeting Member Join |

Legacy Names
------------
| Success                            | Fail |
| ---------------------------------- | ---- |
| web-meeting-participant-joined<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#meeting-member-joinsuccess) or a [fail](#meeting-member-joinfail).


meeting-member-join:success
---------------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| member | &#10003; | &#10003;  |               |

A failure activity is not currently supported for this activity-type.