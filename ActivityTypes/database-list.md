database-list
=============

Description
-----------
Database resources were enumerated on the database

Parameters
----------
| Parameter     | Value         |
| ------------- | ------------- |
| Subject       | database      |
| Activity      | list          |
| Activity Type | database-list |
| Pretty Name   | Database List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-listsuccess) or a [fail](#database-listfail).


database-list:success
---------------------

There are no fields for this activity type.


database-list:fail
------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |