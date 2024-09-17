site_collector-create
=====================

Description
-----------
Site Collector Created

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | site_collector        |
| Activity      | create                |
| Activity Type | site_collector-create |
| Pretty Name   | Site Collector Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#site_collector-createsuccess) or a [fail](#site_collector-createfail).


site_collector-create:success
-----------------------------

There are no fields for this activity type.


site_collector-create:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |