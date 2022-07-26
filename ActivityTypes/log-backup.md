log-backup
==========

Description
-----------
An audit log was backed up

Parameters
----------
| Parameter     | Value      |
| ------------- | ---------- |
| Subject       | log        |
| Activity      | backup     |
| Activity Type | log-backup |
| Pretty Name   | Log Backup |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#log-backupsuccess) or a [fail](#log-backupfail).


log-backup:success
------------------

There are no fields for this activity type.


log-backup:fail
---------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |