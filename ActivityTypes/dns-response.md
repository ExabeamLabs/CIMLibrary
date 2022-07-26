dns-response
============

Description
-----------
A DNS response was recevied

Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | dns          |
| Activity      | response     |
| Activity Type | dns-response |
| Pretty Name   | Dns Response |

Legacy Names
------------
| Success          | Fail             |
| ---------------- | ---------------- |
| dns-response<br> | dns-response<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dns-responsesuccess) or a [fail](#dns-responsefail).


dns-response:success
--------------------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| dns_response       | &#10003; | &#10003;  |               |
| dns_response_code  |          | &#10003;  |               |
| dns_response_flags |          | &#10003;  |               |

dns-response:fail
-----------------

| Field              | Core     | Detection | Informational |
| ------------------ | -------- | --------- | ------------- |
| failure_code       |          | &#10003;  |               |
| dns_response       | &#10003; | &#10003;  |               |
| dns_response_code  |          | &#10003;  |               |
| dns_response_flags |          | &#10003;  |               |
| failure_reason     |          | &#10003;  |               |