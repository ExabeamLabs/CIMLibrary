meeting-modify
==============

Description
-----------
A web meeting's information was updated

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | meeting        |
| Activity      | modify         |
| Activity Type | meeting-modify |
| Pretty Name   | Meeting Modify |

Legacy Names
------------
| Success                 | Fail                    |
| ----------------------- | ----------------------- |
| web-meeting-updated<br> | web-meeting-updated<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#meeting-modifysuccess) or a [fail](#meeting-modifyfail).


meeting-modify:success
----------------------

| Field        | Core | Detection | Informational |
| ------------ | ---- | --------- | ------------- |
| old_password |      | &#10003;  |               |
| new_password |      | &#10003;  |               |

meeting-modify:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| old_password   |      | &#10003;  |               |
| new_password   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |