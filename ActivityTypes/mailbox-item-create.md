mailbox-item-create
===================

Description
-----------
An item contained in an email mailbox was created

Parameters
----------
| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | mailbox             |
| Activity      | item-create         |
| Activity Type | mailbox-item-create |
| Pretty Name   | Mailbox Item Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-item-createsuccess) or a [fail](#mailbox-item-createfail).


mailbox-item-create:success
---------------------------

There are no fields for this activity type.


mailbox-item-create:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |