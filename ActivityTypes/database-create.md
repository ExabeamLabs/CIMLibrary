database-create
===============

Description
-----------
A database resource was created

Parameters
----------
| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | database        |
| Activity      | create          |
| Activity Type | database-create |
| Pretty Name   | Database Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-createsuccess) or a [fail](#database-createfail).


database-create:success
-----------------------

There are no fields for this activity type.


database-create:fail
--------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |