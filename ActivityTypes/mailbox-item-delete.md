mailbox-item-delete
===================

Description
-----------
An item contained in an email mailbox was deleted

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | mailbox             |
| Activity      | item-delete         |
| Activity Type | mailbox-item-delete |
| Pretty Name   | Mailbox Item Delete |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-item-deletesuccess) or a [fail](#mailbox-item-deletefail).


mailbox-item-delete:success
---------------------------

There are no fields for this activity type.


mailbox-item-delete:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |