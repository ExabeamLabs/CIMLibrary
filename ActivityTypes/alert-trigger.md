alert-trigger
=============

Description
-----------
An instance of an alert was triggered on the security product

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | alert         |
| Activity      | trigger       |
| Activity Type | alert-trigger |
| Pretty Name   | Alert Trigger |

Legacy Names
------------
| Success                                                                                                        | Fail |
| -------------------------------------------------------------------------------------------------------------- | ---- |
| security-alert<br>process-alert<br>file-alert<br>network-alert<br>dlp-alert<br>database-alert<br>alert-iot<br> |      |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#alert-triggersuccess) or a [fail](#alert-triggerfail).


alert-trigger:success
---------------------

| Field          | Core     | Detection | Informational |
| -------------- | -------- | --------- | ------------- |
| alert_severity | &#10003; |           |               |
| alert_source   | &#10003; |           |               |
| alert_subject  |          |           | &#10003;      |
| alert_type     | &#10003; |           |               |

A failure activity is not currently supported for this activity-type.