bucket-permission-read
======================

Description
-----------
The ACL or any other passive permission configuration applied to the bucket was read

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | bucket                 |
| Activity      | permission-read        |
| Activity Type | bucket-permission-read |
| Pretty Name   | Bucket Permission Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-permission-readsuccess) or a [fail](#bucket-permission-readfail).


bucket-permission-read:success
------------------------------

There are no fields for this activity type.


bucket-permission-read:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |