certificate-exchange
====================

Description
-----------
A digital certificate was exchanged with another in the process of an end to end authenticity check

Parameters
----------
| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | certificate          |
| Activity      | exchange             |
| Activity Type | certificate-exchange |
| Pretty Name   | Certificate Exchange |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#certificate-exchangesuccess) or a [fail](#certificate-exchangefail).


certificate-exchange:success
----------------------------

There are no fields for this activity type.


certificate-exchange:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |