log-clear
=========

Description
-----------
An audit log was cleared

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | log       |
| Activity      | clear     |
| Activity Type | log-clear |
| Pretty Name   | Log Clear |

Legacy Names
------------
| Success             | Fail                |
| ------------------- | ------------------- |
| audit-log-clear<br> | audit-log-clear<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-clearsuccess) or a [fail](#log-clearfail).


log-clear:success
-----------------

There are no fields for this activity type.


log-clear:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |