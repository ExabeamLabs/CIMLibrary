dns_record-modify
=================

Description
-----------
The content of a DNS record was modified

The possible fields for this activity type will vary depending on whether the activity was a [success](#dns_record-modifysuccess) or a [fail](#dns_record-modifyfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | dns_record        |
| Activity      | modify            |
| Activity Type | dns_record-modify |
| Pretty Name   | Dns_record Modify |
| Legacy Name   |                   |

dns_record-modify:success
-------------------------

There are no fields for this activity type.


dns_record-modify:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |