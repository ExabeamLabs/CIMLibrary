bucket-list
===========

Description
-----------
Buckets were enumerated on the application

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-listsuccess) or a [fail](#bucket-listfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | bucket      |
| Activity      | list        |
| Activity Type | bucket-list |
| Pretty Name   | Bucket List |
| Legacy Name   |             |

bucket-list:success
-------------------

There are no fields for this activity type.


bucket-list:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |