assetview
=========

Expression
----------

product = "assetview"

Fields
------

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| domain           |          |           | &#10003;      |
| domain_user_name |          |           |               |
| user             | &#10003; | &#10003;  |               |

Activity Types
--------------

| Activity Type             | Field             | Status | Core     | Detection | Informational |
| ------------------------- | ----------------- | ------ | -------- | --------- | ------------- |
| file-download             | process_name      | Legacy |          |           | &#10003;      |
| file-write                | process_name      | Legacy |          |           | &#10003;      |
|                           | asset_id          |        |          |           | &#10003;      |
| peripheral_storage-insert | usb_vendor        |        |          |           | &#10003;      |
|                           | vendor_id         |        |          |           | &#10003;      |
|                           | usb_serial_number |        |          |           | &#10003;      |
| printer-activity          | file_name         | Legacy | &#10003; | &#10003;  |               |
|                           | num_pages         | Legacy |          | &#10003;  |               |
|                           | printer_name      | Legacy | &#10003; | &#10003;  |               |
|                           | asset_id          |        |          |           | &#10003;      |

