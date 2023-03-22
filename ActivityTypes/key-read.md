key-read
========

Description
-----------
A request was made to read the content or properties of a key

Parameters
----------
| Parameter     | Value    |
| ------------- | -------- |
| Subject       | key      |
| Activity      | read     |
| Activity Type | key-read |
| Pretty Name   | Key Read |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#key-readsuccess) or a [fail](#key-readfail).


key-read:success
----------------

There are no fields for this activity type.


key-read:fail
-------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |