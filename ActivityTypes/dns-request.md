dns-request
===========

Description
-----------
A DNS query was sent

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | dns         |
| Activity      | request     |
| Activity Type | dns-request |
| Pretty Name   | Dns Request |

Legacy Names
------------
| Success       | Fail          |
| ------------- | ------------- |
| dns-query<br> | dns-query<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dns-requestsuccess) or a [fail](#dns-requestfail).


dns-request:success
-------------------

There are no fields for this activity type.


dns-request:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |