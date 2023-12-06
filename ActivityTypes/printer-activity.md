printer-activity
================

Description
-----------
An activity in a printer

Parameters
----------
| Parameter     | Value            |
| ------------- | ---------------- |
| Subject       | printer          |
| Activity      | activity         |
| Activity Type | printer-activity |
| Pretty Name   | Printer Activity |

Legacy Names
------------
| Success            | Fail |
| ------------------ | ---- |
| print-activity<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#printer-activitysuccess) or a [fail](#printer-activityfail).


printer-activity:success
------------------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| bytes           |          | &#10003;  |               |
| num_pages       |          | &#10003;  |               |
| local_user_name |          |           |               |
| printer_name    |          | &#10003;  |               |
| operation       | &#10003; |           |               |
| user            |          | &#10003;  |               |

A failure activity is not currently supported for this activity-type.