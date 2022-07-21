log-download
============

Description
-----------
An audit log was downloaded from a remote site

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-downloadsuccess) or a [fail](#log-downloadfail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | log          |
| Activity      | download     |
| Activity Type | log-download |
| Pretty Name   | Log Download |
| Legacy Name   |              |

log-download:success
--------------------

There are no fields for this activity type.


log-download:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |