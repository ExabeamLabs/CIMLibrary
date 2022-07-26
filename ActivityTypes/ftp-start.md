ftp-start
=========

Description
-----------
A FTP network session was initiated

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | ftp       |
| Activity      | start     |
| Activity Type | ftp-start |
| Pretty Name   | Ftp Start |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ftp-startsuccess) or a [fail](#ftp-startfail).


ftp-start:success
-----------------

There are no fields for this activity type.


ftp-start:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |