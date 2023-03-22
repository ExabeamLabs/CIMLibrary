configuration-mfa-disable
=========================

Description
-----------
The global mfa configuration of an application was changed to disabled

Parameters
----------
| Parameter     | Value                     |
| ------------- | ------------------------- |
| Subject       | configuration             |
| Activity      | mfa-disable               |
| Activity Type | configuration-mfa-disable |
| Pretty Name   | Configuration Mfa Disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#configuration-mfa-disablesuccess) or a [fail](#configuration-mfa-disablefail).


configuration-mfa-disable:success
---------------------------------

There are no fields for this activity type.


configuration-mfa-disable:fail
------------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |