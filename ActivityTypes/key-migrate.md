key-migrate
===========

Description
-----------
A global key object was migrated between vaults

Parameters
----------
| Parameter     | Value       |
| ------------- | ----------- |
| Subject       | key         |
| Activity      | migrate     |
| Activity Type | key-migrate |
| Pretty Name   | Key Migrate |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#key-migratesuccess) or a [fail](#key-migratefail).


key-migrate:success
-------------------

There are no fields for this activity type.


key-migrate:fail
----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |