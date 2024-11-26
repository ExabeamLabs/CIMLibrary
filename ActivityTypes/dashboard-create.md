dashboard-create
================

Description
-----------
A Dashboard was created 

Parameters
----------
| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | dashboard         |
| Activity      | create            |
| Activity Type | dashboard-create  |
| Pretty Name   | Dashboard Created |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#dashboard-createsuccess) or a [fail](#dashboard-createfail).


dashboard-create:success
------------------------

There are no fields for this activity type.


dashboard-create:fail
---------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |