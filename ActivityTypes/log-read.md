log-read
========

Description
-----------
A request was made to read the content of a log

Parameters
----------
| Parameter     | Value    |
| ------------- | -------- |
| Subject       | log      |
| Activity      | read     |
| Activity Type | log-read |
| Pretty Name   | Log Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-readsuccess) or a [fail](#log-readfail).


log-read:success
----------------

There are no fields for this activity type.


log-read:fail
-------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |