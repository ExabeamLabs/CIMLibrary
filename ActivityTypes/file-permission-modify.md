file-permission-modify
======================

Description
-----------
The permissions that apply to a file were changed

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | file                   |
| Activity      | permission-modify      |
| Activity Type | file-permission-modify |
| Pretty Name   | File Permission Modify |

Legacy Names
------------
| Success                    | Fail                       |
| -------------------------- | -------------------------- |
| file-permission-change<br> | file-permission-change<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-permission-modifysuccess) or a [fail](#file-permission-modifyfail).


file-permission-modify:success
------------------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| acl_content |      |           | &#10003;      |
| permissions |      | &#10003;  |               |
| bucket_name |      |           | &#10003;      |

file-permission-modify:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| acl_content    |      |           | &#10003;      |
| failure_code   |      | &#10003;  |               |
| permissions    |      | &#10003;  |               |
| bucket_name    |      |           | &#10003;      |
| failure_reason |      | &#10003;  |               |