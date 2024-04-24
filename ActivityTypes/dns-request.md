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

| Field    | Core | Detection | Informational |
| -------- | ---- | --------- | ------------- |
| bytes    |      | &#10003;  |               |
| src_host |      | &#10003;  |               |

dns-request:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| bytes          |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |
| src_host       |      | &#10003;  |               |