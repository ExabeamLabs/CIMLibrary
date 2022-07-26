mailbox-delete
==============

Description
-----------
An email mailbox was deleted

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | mailbox        |
| Activity      | delete         |
| Activity Type | mailbox-delete |
| Pretty Name   | Mailbox Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-deletesuccess) or a [fail](#mailbox-deletefail).


mailbox-delete:success
----------------------

There are no fields for this activity type.


mailbox-delete:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |