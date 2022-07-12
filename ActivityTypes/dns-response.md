dns-response
============

Description
-----------
A DNS response was recevied

The possible fields for this activity type will vary depending on whether the activity was a [success](#dns-responsesuccess) or a [fail](#dns-responsefail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | dns          |
| Activity      | response     |
| Activity Type | dns-response |
| Pretty Name   | Dns Response |
| Legacy Name   |              |

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
| dns_response       | &#10003; | &#10003;  |               |
| dns_response_code  |          | &#10003;  |               |
| dns_response_flags |          | &#10003;  |               |