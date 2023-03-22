endpoint-policy-verify
======================

Description
-----------
An endpoint policy was verified

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | endpoint               |
| Activity      | policy-verify          |
| Activity Type | endpoint-policy-verify |
| Pretty Name   | Endpoint Policy Verify |

Legacy Names
------------
| Success       | Fail                 |
| ------------- | -------------------- |
| nac-logon<br> | nac-failed-logon<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#endpoint-policy-verifysuccess) or a [fail](#endpoint-policy-verifyfail).


endpoint-policy-verify:success
------------------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| src_ip | &#10003; |           |               |

endpoint-policy-verify:fail
---------------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| src_ip         | &#10003; |           |               |
| failure_code   |          | &#10003;  |               |
| failure_reason |          | &#10003;  |               |