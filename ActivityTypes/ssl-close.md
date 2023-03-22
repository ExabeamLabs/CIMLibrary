ssl-close
=========

Description
-----------
A SSL session was terminated

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | ssl       |
| Activity      | close     |
| Activity Type | ssl-close |
| Pretty Name   | Ssl Close |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#ssl-closesuccess) or a [fail](#ssl-closefail).


ssl-close:success
-----------------

There are no fields for this activity type.


ssl-close:fail
--------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |