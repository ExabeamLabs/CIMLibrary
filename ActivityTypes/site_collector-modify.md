site_collector-modify
=====================

Description
-----------
Site Collector modified

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | site_collector        |
| Activity      | modify                |
| Activity Type | site_collector-modify |
| Pretty Name   | Site Collector modify |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#site_collector-modifysuccess) or a [fail](#site_collector-modifyfail).


site_collector-modify:success
-----------------------------

There are no fields for this activity type.


site_collector-modify:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |