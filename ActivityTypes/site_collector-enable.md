site_collector-enable
=====================

Description
-----------
Site Collector was enabled

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | site_collector        |
| Activity      | enable                |
| Activity Type | site_collector-enable |
| Pretty Name   | Site Collector enable |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#site_collector-enablesuccess) or a [fail](#site_collector-enablefail).


site_collector-enable:success
-----------------------------

There are no fields for this activity type.


site_collector-enable:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |