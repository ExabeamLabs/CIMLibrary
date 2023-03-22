audit_policy-modify
===================

Description
-----------
An audit policy was modified

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | audit_policy        |
| Activity      | modify              |
| Activity Type | audit_policy-modify |
| Pretty Name   | Audit_policy Modify |

Legacy Names
------------
| Success                 | Fail                    |
| ----------------------- | ----------------------- |
| audit-policy-change<br> | audit-policy-change<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#audit_policy-modifysuccess) or a [fail](#audit_policy-modifyfail).


audit_policy-modify:success
---------------------------

There are no fields for this activity type.


audit_policy-modify:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |