file-read
=========

Description
-----------
A file was opened/read

Parameters
----------
| Parameter     | Value     |
| ------------- | --------- |
| Subject       | file      |
| Activity      | read      |
| Activity Type | file-read |
| Pretty Name   | File Read |

Legacy Names
------------
| Success                   | Fail                      |
| ------------------------- | ------------------------- |
| file-read<br>usb-read<br> | file-read<br>usb-read<br> |

Fields
------

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-readsuccess) or a [fail](#file-readfail).


file-read:success
-----------------

| Field                 | Core | Detection | Informational |
| --------------------- | ---- | --------- | ------------- |
| is_dok                |      | &#10003;  |               |
| is_peripheral_storage |      | &#10003;  |               |
| device_pid            |      | &#10003;  |               |
| storage_account       |      | &#10003;  |               |
| device_vid            |      | &#10003;  |               |
| cid                   |      |           | &#10003;      |

file-read:fail
--------------

| Field           | Core | Detection | Informational |
| --------------- | ---- | --------- | ------------- |
| failure_code    |      | &#10003;  |               |
| is_dok          |      | &#10003;  |               |
| failure_reason  |      | &#10003;  |               |
| storage_account |      | &#10003;  |               |
| cid             |      |           | &#10003;      |