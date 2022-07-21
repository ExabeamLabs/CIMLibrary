tanium integrity monitor
========================

Expression
----------

product = "tanium integrity monitor"

Fields
------

There are no fields for this extension.

Activity Types
--------------

| Activity Type          | Field        | Status | Core     | Detection | Informational |
| ---------------------- | ------------ | ------ | -------- | --------- | ------------- |
| file-delete            | proess_path  |        |          |           |               |
|                        | access       | Legacy |          | &#10003;  |               |
|                        | process_name | Legacy |          |           | &#10003;      |
|                        | event_name   |        |          |           |               |
|                        | src_host     | Legacy |          | &#10003;  |               |
|                        | user         | Legacy | &#10003; | &#10003;  |               |
| file-permission-modify | proess_path  |        |          |           |               |
|                        | access       | Legacy |          | &#10003;  |               |
|                        | process_name | Legacy |          |           | &#10003;      |
|                        | event_name   |        |          |           |               |
|                        | src_host     |        |          |           |               |
|                        | user         | Legacy | &#10003; | &#10003;  |               |
| file-write             | proess_path  |        |          |           |               |
|                        | access       | Legacy |          | &#10003;  |               |
|                        | process_name | Legacy |          |           | &#10003;      |
|                        | event_name   |        |          |           |               |
|                        | src_host     |        |          |           |               |
|                        | user         | Legacy | &#10003; | &#10003;  |               |

