ftp-traffic
===========

Description
-----------
A representation of a single FTP packet

The possible fields for this activity type will vary depending on whether the activity was a [success](#ftp-trafficsuccess) or a [fail](#ftp-trafficfail).

| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | ftp         |
| Activity      | traffic     |
| Activity Type | ftp-traffic |
| Pretty Name   | Ftp Traffic |
| Legacy Name   |             |

ftp-traffic:success
-------------------

There are no fields for this activity type.


ftp-traffic:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |