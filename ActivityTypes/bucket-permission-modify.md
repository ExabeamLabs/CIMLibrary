bucket-permission-modify
========================

Description
-----------
The ACL or any other passive permission configuration applied to the bucket was updated

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-permission-modifysuccess) or a [fail](#bucket-permission-modifyfail).

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Subject       | bucket                   |
| Activity      | permission-modify        |
| Activity Type | bucket-permission-modify |
| Pretty Name   | Bucket Permission Modify |
| Legacy Name   |                          |

bucket-permission-modify:success
--------------------------------

There are no fields for this activity type.


bucket-permission-modify:fail
-----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |