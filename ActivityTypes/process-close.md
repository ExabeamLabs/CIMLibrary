process-close
=============

Description
-----------
A process was terminated

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | process       |
| Activity      | close         |
| Activity Type | process-close |
| Pretty Name   | Process Close |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#process-closesuccess) or a [fail](#process-closefail).


process-close:success
---------------------

There are no fields for this activity type.


process-close:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |