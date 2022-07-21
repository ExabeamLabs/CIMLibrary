dns_record-delete
=================

Description
-----------
A DNS record was deleted

The possible fields for this activity type will vary depending on whether the activity was a [success](#dns_record-deletesuccess) or a [fail](#dns_record-deletefail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | dns_record        |
| Activity      | delete            |
| Activity Type | dns_record-delete |
| Pretty Name   | Dns_record Delete |
| Legacy Name   |                   |

dns_record-delete:success
-------------------------

There are no fields for this activity type.


dns_record-delete:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |