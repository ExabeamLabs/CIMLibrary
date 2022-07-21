mailbox-item-modify
===================

Description
-----------
The properties or content of an item contained in an email mailbox were changed

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-item-modifysuccess) or a [fail](#mailbox-item-modifyfail).

| Parameter     | Value               |
| ------------- | ------------------- |
| Subject       | mailbox             |
| Activity      | item-modify         |
| Activity Type | mailbox-item-modify |
| Pretty Name   | Mailbox Item Modify |
| Legacy Name   |                     |

mailbox-item-modify:success
---------------------------

There are no fields for this activity type.


mailbox-item-modify:fail
------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |