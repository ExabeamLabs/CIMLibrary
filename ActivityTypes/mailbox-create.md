mailbox-create
==============

Description
-----------
An email mailbox was created

Parameters
----------
| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | mailbox        |
| Activity      | create         |
| Activity Type | mailbox-create |
| Pretty Name   | Mailbox Create |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-createsuccess) or a [fail](#mailbox-createfail).


mailbox-create:success
----------------------

There are no fields for this activity type.


mailbox-create:fail
-------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |