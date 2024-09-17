site_collector-disable
======================

Description
-----------
Site Collector was disabled

Parameters
----------
| Parameter     | Value                  |
| ------------- | ---------------------- |
| Subject       | site_collector         |
| Activity      | disable                |
| Activity Type | site_collector-disable |
| Pretty Name   | Site Collector disable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#site_collector-disablesuccess) or a [fail](#site_collector-disablefail).


site_collector-disable:success
------------------------------

There are no fields for this activity type.


site_collector-disable:fail
---------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |