service-create
==============

Description
-----------
A service was created

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | service        |
| Activity      | create         |
| Activity Type | service-create |
| Pretty Name   | Service Create |

Legacy Names
------------
| Success             | Fail |
| ------------------- | ---- |
| service-created<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#service-createsuccess) or a [fail](#service-createfail).


service-create:success
----------------------

| Field                | Core | Detection | Informational |
| -------------------- | ---- | --------- | ------------- |
| process_path         |      | &#10003;  |               |
| process_command_line |      | &#10003;  |               |
| user                 |      | &#10003;  |               |

A failure activity is not currently supported for this activity-type.