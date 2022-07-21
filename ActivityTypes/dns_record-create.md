dns_record-create
=================

Description
-----------
A DNS record was created

The possible fields for this activity type will vary depending on whether the activity was a [success](#dns_record-createsuccess) or a [fail](#dns_record-createfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | dns_record        |
| Activity      | create            |
| Activity Type | dns_record-create |
| Pretty Name   | Dns_record Create |
| Legacy Name   |                   |

dns_record-create:success
-------------------------

There are no fields for this activity type.


dns_record-create:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |