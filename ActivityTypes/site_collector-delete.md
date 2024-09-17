site_collector-delete
=====================

Description
-----------
Site Collector was deleted

Parameters
----------
| Parameter     | Value                 |
| ------------- | --------------------- |
| Subject       | site_collector        |
| Activity      | delete                |
| Activity Type | site_collector-delete |
| Pretty Name   | Site Collector delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#site_collector-deletesuccess) or a [fail](#site_collector-deletefail).


site_collector-delete:success
-----------------------------

There are no fields for this activity type.


site_collector-delete:fail
--------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |