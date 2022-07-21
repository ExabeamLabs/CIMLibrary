mailbox-item-read
=================

Description
-----------
The content of an item contained in an email mailbox was read

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-item-readsuccess) or a [fail](#mailbox-item-readfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | mailbox           |
| Activity      | item-read         |
| Activity Type | mailbox-item-read |
| Pretty Name   | Mailbox Item Read |
| Legacy Name   |                   |

mailbox-item-read:success
-------------------------

There are no fields for this activity type.


mailbox-item-read:fail
----------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| failure_code   |      | &#10003;  |               |
| failure_reason |      | &#10003;  |               |