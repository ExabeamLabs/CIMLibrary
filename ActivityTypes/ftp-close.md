ftp-close
=========

Description
-----------
A FTP network session was closed

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | ftp       |
| Activity      | close     |
| Activity Type | ftp-close |
| Pretty Name   | Ftp Close |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ftp-closesuccess) or a [fail](#ftp-closefail).


ftp-close:success
-----------------

There are no fields for this activity type.


ftp-close:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |