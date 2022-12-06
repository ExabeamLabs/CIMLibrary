mailbox-list
============

Description
-----------


Parameters
----------
| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | mailbox      |
| Activity      | list         |
| Activity Type | mailbox-list |
| Pretty Name   | Mailbox List |


Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-listsuccess) or a [fail](#mailbox-listfail).


mailbox-list:success
--------------------

There are no fields for this activity type.


mailbox-list:fail
-----------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |