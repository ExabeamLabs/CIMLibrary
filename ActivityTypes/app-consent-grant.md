app-consent-grant
=================

Description
-----------
Consent was granted to an application

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | app                 |
| Activity      | consent-grant       |
| Activity Type | app-consent-grant   |
| Pretty Name   | App Consent Granted |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#app-consent-grantsuccess) or a [fail](#app-consent-grantfail).


app-consent-grant:success
-------------------------

| Field      | Core | Detection | Informational |
| ---------- | ---- | --------- | ------------- |
| app        |      | &#10003;  |               |
| permission |      | &#10003;  |               |

A failure activity is not currently supported for this activity-type.