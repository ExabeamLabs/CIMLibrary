endpoint-modify
===============

Description
-----------
An endpoint object or instance properties\configuration were modified

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | endpoint        |
| Activity      | modify          |
| Activity Type | endpoint-modify |
| Pretty Name   | Endpoint Modify |

Legacy Names
------------
| Success | Fail   |
| ------- | ------ |
| NA<br>  | NA<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-modifysuccess) or a [fail](#endpoint-modifyfail).


endpoint-modify:success
-----------------------

There are no fields for this activity type.


endpoint-modify:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |