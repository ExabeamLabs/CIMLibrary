mailbox-item-move
=================

Description
-----------
An item contained in an email mailbox was moved from one folder or maiblox to another

The possible fields for this activity type will vary depending on whether the activity was a [success](#mailbox-item-movesuccess) or a [fail](#mailbox-item-movefail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | mailbox           |
| Activity      | item-move         |
| Activity Type | mailbox-item-move |
| Pretty Name   | Mailbox Item Move |
| Legacy Name   |                   |

mailbox-item-move:success
-------------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| dest_email_folder |      |           | &#10003;      |
| src_email_folder  |      |           | &#10003;      |

mailbox-item-move:fail
----------------------

| Field             | Core | Detection | Informational |
| ----------------- | ---- | --------- | ------------- |
| dest_email_folder |      |           | &#10003;      |
| failure_code      |      | &#10003;  |               |
| src_email_folder  |      |           | &#10003;      |
| failure_reason    |      | &#10003;  |               |