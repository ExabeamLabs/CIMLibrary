bucket-accessblock-modify
=========================

Description
-----------
The public access block configuration of a bucket was changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-accessblock-modifysuccess) or a [fail](#bucket-accessblock-modifyfail).

| Parameter     | Value                     |
| ------------- | ------------------------- |
| Subject       | bucket                    |
| Activity      | accessblock-modify        |
| Activity Type | bucket-accessblock-modify |
| Pretty Name   | Bucket Accessblock Modify |
| Legacy Name   |                           |

bucket-accessblock-modify:success
---------------------------------

There are no fields for this activity type.


bucket-accessblock-modify:fail
------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |