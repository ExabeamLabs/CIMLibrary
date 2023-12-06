physical_location-access
========================

Description
-----------
A user opened a door, gate, or any other entrance using their badge

Parameters
----------
| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | physical_location        |
| Activity      | access                   |
| Activity Type | physical_location-access |
| Pretty Name   | Physical_location Access |

Legacy Names
------------
| Success             | Fail                       |
| ------------------- | -------------------------- |
| physical-access<br> | failed-physical-access<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#physical_location-accesssuccess) or a [fail](#physical_location-accessfail).


physical_location-access:success
--------------------------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| local_user_name |          |           |               |
| user            | &#10003; | &#10003;  |               |

physical_location-access:fail
-----------------------------

| Field           | Core     | Detection | Informational |
| --------------- | -------- | --------- | ------------- |
| failure_code    |          | &#10003;  |               |
| local_user_name |          |           |               |
| failure_reason  |          | &#10003;  |               |
| user            | &#10003; | &#10003;  |               |